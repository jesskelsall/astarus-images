# Dungeons & Dragons: Astarus Images

<img src="https://raw.githubusercontent.com/jesskelsall/astarus-images/main/symbols/556ce67a6c183e48.png" height="100">

A bunch of images with random IDs, because making all of my D&D notes public is a bad idea.

## Where Mortals Fear to Tread...

If you are reading this and play D&D with me, please go no further.  
There are spoilers ahead.  
You'll only be robbing yourself of future excitement.

---

## Making New IDs

```javascript
const nanoid = require('nanoid')
const random = nanoid.customAlphabet('1234567890abcdef', 16)

random()
```