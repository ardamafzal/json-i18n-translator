# JSON i18n Translator

Translate JSON i18n files without breaking keys or placeholders.

## Problem

AI tools often break JSON when translating:

- Keys get changed  
- Placeholders like `{name}` or `%d` break  
- Output becomes invalid JSON  

This makes it unusable in production.

## Solution

This tool guarantees:

- ✅ Keys preserved  
- ✅ Placeholders intact  
- ✅ Valid JSON  
- ✅ Ready-to-use output  

## Demo

![Demo](./screenshot.png)

## Try it

👉 https://your-link-here

## Example

**Input**
```json
{
  "welcome": "Welcome {name}",
  "messages": "You have {count} new messages"
}
