# [SDF10] Project: Mobile App

# Add to Cart Project

This project provides a basic "Add to Cart" functionality using HTML, CSS, and JavaScript. It demonstrates how to capture user input and handle events to simulate adding items to a shopping cart.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [HTML Structure](#html-structure)
- [CSS Styling](#css-styling)
- [JavaScript Functionality](#javascript-functionality)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository to your local machine:
   git clone https://github.com/yourusername/add-to-cart.git

2. Navigate to the project directory:
3. 
    cd add-to-cart
  
4. Open `index.html` in your web browser to view the project.

## Usage

1. Enter an item into the input field.
2. Click the "Add to Cart" button to simulate adding the item to the cart.
3. The item entered will be logged to the console.

## Code Overview

### HTML Structure

The HTML file contains the structure of the page, including an input field and a button for adding items to the cart.


### CSS Styling

The CSS file styles the page to ensure a clean and simple interface. Key styles include:

- Margin and padding reset for `html` and `body`
- Container centering and styling



### JavaScript Functionality

The JavaScript file handles the logic for adding items to the cart. It includes an event listener for the button click and logs the input value to the console.

javascript
const inputFieldEl = document.getElementById("input-field")
const addButtonEl = document.getElementById("add-button")

addButtonEl.addEventListener("click", function() {
    let inputValue = inputFieldEl.value
    console.log(inputValue)
})

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.


Authored by Dumisani Nxumalo.
