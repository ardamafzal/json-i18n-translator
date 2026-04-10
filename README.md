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
<img width="1017" height="787" alt="image" src="https://github.com/user-attachments/assets/5e55285b-1f34-4d89-90b4-3c5b8fa39b42" />
