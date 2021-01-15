# color-flipper

<h3>This is the first project of FreeCodeCamp's Javascript tutorials. </h3>

The takeaway is: how to use Math.random()

1. Math.random() with values of an array (app.js):

function getRandomNumber() {

 return Math.floor(Math.random() * colors.length)

}

2. Math.random() with multiple values (hex.js)

let hexColor = "#";
for (let i = 0; i<6; i++) {

    hexColor+= hex[getRandomNumber()]

}

