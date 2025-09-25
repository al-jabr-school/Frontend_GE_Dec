# Lesson 01 - Introduction

Biz bu tillarni o'rganamiz:

- **HTML**: Hyper-Text Markup Language
- **CSS**: Cascading Style Sheet
- **JavaScript**
- **React.js**
- **Tailwind CSS**

## HTML

HTML - saytning strukturasi

```html
<html>
  <head>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
  </head>
  <body>
    <h1>Hello world</h1>
  </body>
</html>
```

- **head**: HTMLning bosh qismi. CSS, JavaScript and sayt haqida ma'lumotlarni qo'shish uchun ishlatiladi.
- **body**: Saytda ko'rinadigan barcha elementlar.
- **defer**: HTMLning yuklagandan keyin JavaScriptning yugurish uslubi.
- **DOCTYPE**: faylni HTML bilan XML ni farqini aniqlash. 
- **UTF-8**: saytlar uchun xalqaro standart turi
- **lang="uz"**: browzerga sayt tilini aytish uchun. Tajrima qilishda.

## CSS

CSS - saytning dizayni.

```css
body {
  background-color: black;
}

h1 {
  color: white;
}
```

## JavaScript

JavaScript - saytning funksiyasi.

```js
const olmaNarxi = 5000;

function narxniAniqlash(kg) {
  return olmaNarxi * kg;
}

narxniAniqlash(10); // 5000 * 10 = 50000
```

## React.js

React - JavaScript ichida HTML yozish.

```jsx
function Sarlavha() {
  return (
    <h1>Hello world</h1>
  )
}
```

- **jsx**: React fayl formati (masalan, ".html")

## Tailwind CSS

Tailwind - HTML ichida CSS yozish.

```html
<body class="bg-white">
  <h1 class="text-white"></h1>
</body>
```