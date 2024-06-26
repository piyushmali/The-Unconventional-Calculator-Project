# The Unconventional Calculator Project 🧮

Welcome to the Unconventional Calculator Project! This project offers a fun and interactive web-based calculator for performing basic arithmetic operations. Whether you prefer control statements or a more streamlined experience, we've got you covered with two versions of the calculator. 🎉

## Table of Contents
- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)

## Introduction

The Unconventional Calculator Project aims to provide users with a unique and engaging way to perform mathematical calculations. With its unconventional interface and user-friendly design, this calculator makes math fun! 😄

## Repository Structure

### 1. The Unconventional Calculator Project With Control Statements

This version of the calculator includes control statements (if-else) for handling different arithmetic operations.

#### Summary
The calculator with control statements offers a traditional approach to handling arithmetic operations. It utilizes conditional statements to determine the operation to perform based on user input.

#### Structure

- **index.html**: HTML file containing the structure of the calculator interface.
- **app.js**: JavaScript file containing the logic for performing calculations and handling user inputs.
- **vendor.js**: JavaScript file containing vendor-specific scripts.
- **app.css**: CSS file for styling the calculator interface.

#### Logic Explanation
- The `calculateResult()` function in `app.js` checks the calculation type (addition, subtraction, multiplication, or division) using conditional statements and performs the corresponding operation.
- User input is validated to ensure it is a valid number before performing calculations.

### 2. The Unconventional Calculator Project Without Control Statements

This version of the calculator omits control statements and directly performs calculations based on user inputs.

#### Summary
The calculator without control statements provides a simplified approach to arithmetic operations. It directly performs calculations based on user input without the need for conditional statements.

#### Structure

- **index.html**: HTML file containing the structure of the calculator interface.
- **app.js**: JavaScript file containing the logic for performing calculations and handling user inputs.
- **vendor.js**: JavaScript file containing vendor-specific scripts.
- **app.css**: CSS file for styling the calculator interface.

#### Logic Explanation
- Each arithmetic operation (addition, subtraction, multiplication, division) has its own dedicated function (`add()`, `subtract()`, `multiply()`, `divide()`) in `app.js`.
- These functions directly perform calculations based on user input without the need for conditional statements.

## Usage

1. Clone the repository to your local machine.
2. Open the desired version of the calculator (with or without control statements) in a web browser.
3. Enter numbers and click on the appropriate operation buttons to perform calculations.
4. The result will be displayed in real-time on the interface.

## Contributions

We welcome contributions from the community to make this project even better! Whether it's fixing bugs, adding new features, or improving the user interface, your contributions are valuable. 🙌

To contribute:
- Fork the repository.
- Make your changes.
- Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). 📝
