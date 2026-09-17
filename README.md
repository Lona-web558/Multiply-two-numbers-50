# Multiply-two-numbers-50


Multiply Two Numbers

A simple HTML and JavaScript program that multiplies two numbers and displays the result in a browser alert.

Description

This project demonstrates a basic JavaScript function, "multiply()", that:

1. Defines two numbers ("5" and "6").
2. Multiplies the numbers together.
3. Displays the product using a browser alert.

The result displayed is:

The product is : 30

Technologies Used

- HTML5
- CSS3
- JavaScript

How to Run

1. Save the HTML code as a file, for example:
   
   index.html

2. Open "index.html" in a web browser.

3. Click the Press Here button.

4. A pop-up alert will display the product of the two numbers.

How It Works

The JavaScript function is:

function multiply() {
    let num1 = 5;
    let num2 = 6;

    let num3;

    num3 = num1 * num2;

    window.alert("The product is : " + num3);
}

The multiplication is performed with the "*" operator:

num3 = num1 * num2;

Since "5 × 6 = 30", the program displays "30".

Project Structure

project/
├── index.html
└── README.md

Author

Created as a simple HTML and JavaScript multiplication exercise.
