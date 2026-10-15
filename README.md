# Simple-Interest-Calculator

A straightforward web application to calculate simple interest based on user-provided inputs for principal, interest rate, and time.

---

## Description

This project is a simple yet functional interest calculator built with HTML, CSS, and vanilla JavaScript. It allows users to input a principal amount, select an interest rate using a dynamic slider, and choose the number of years for the investment. The application then calculates and displays the total interest that will be earned and the future year the amount will be received.

## Features

* **Principal Input**: Accepts any positive numerical value for the principal amount. Includes validation to prevent non-positive entries.
* **Dynamic Rate Slider**: An interactive range slider to easily select the interest rate. The chosen rate is displayed in real-time next to the slider.
* **Year Selection**: A dropdown menu to select the number of years, from 1 to 10.
* **Instant Calculation**: The `compute()` function calculates the simple interest using the formula: `Interest = Principal * Years * Rate / 100`.
* **Clear Results**: The calculated interest and final year are displayed in a user-friendly and highlighted format.
* **Responsive Design**: A clean and centered layout that works on various screen sizes.

## How to Use

To use the calculator, simply open the `index.html` file in your web browser.

1.  **Enter the Principal Amount**: Type the initial amount of money in the "Amount" field.
2.  **Select the Interest Rate**: Drag the slider to set the desired annual interest rate.
3.  **Choose the Number of Years**: Select the investment duration from the dropdown menu.
4.  **Compute**: Click the "Compute Interest" button.

The application will then show you the results right below the button.

## Technologies Used

* **HTML5**: For the structure and content of the web page.
* **CSS3**: For all the styling, including gradients, colors, and layout.
* **JavaScript (ES6)**: To handle the core logic, user interactions, and dynamic content updates.
* **Bootstrap**: For basic button styling.

---

## Author

* Ahmad Almasalkhi

© This Calculator belongs to Ahmad Almasalkhi.
