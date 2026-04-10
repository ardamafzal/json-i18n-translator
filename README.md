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

## Try it

👉 https://localizejson.lovable.app

## Example

**Input**
```json
{
  "welcome": "Welcome {name}",
  "messages": "You have {count} new messages"
}
{
  "welcome": "Bon retour, {name}",
  "messages": "Vous avez {count} nouveaux messages"
}



<img width="1017" height="787" alt="image" src="https://github.com/user-attachments/assets/d922ad25-4d42-4c50-8506-d31f4b8c6eed" />

