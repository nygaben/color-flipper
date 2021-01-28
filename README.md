# color-flipper

This is the first project of FreeCodeCamp's Javascript tutorials (https://www.freecodecamp.org/news/hone-your-javascript-skills-by-building-these-15-projects/)

<h3>The Takeaway is: how to use Math.random()</h3>

1. Math.random() with one value of an array (app.js):
```
function getRandomNumber() {
 return Math.floor(Math.random() * colors.length)
}
```

2. Math.random() with multiple values (hex.js)
```
let hexColor = "#";
for (let i = 0; i<6; i++) {
    hexColor+= hex[getRandomNumber()]
}

function getRandomNumber() {
    return Math.floor(Math.random() * hex.length)
}
```
