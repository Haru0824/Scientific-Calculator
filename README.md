# Scientific Calculator

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Overview

This repository contains a simple yet functional scientific calculator implemented using HTML, CSS, and JavaScript.  It's designed to be a standalone web page that provides both basic arithmetic operations and common scientific calculations.

* **Basic Arithmetic:** Addition (+), Subtraction (-), Multiplication (*), Division (/).
* **Parentheses:** Handles expressions with parentheses `()` for order of operations.
* **Clear and Backspace:**
    * `C` button to clear the display.
    * `←` button for backspace (deleting the last entered character).
* **Scientific Functions:**
    * Square Root: `√` (which is `Math.sqrt()` in JavaScript)
    * Trigonometric Functions:
        * Sine: `sin` (which is `Math.sin()` in JavaScript)
        * Cosine: `cos` (which is `Math.cos()` in JavaScript)
        * Tangent: `tan` (which is `Math.tan()` in JavaScript)
* **Error Handling:** Displays an "Invalid Expression" alert if the input expression is not valid and clears the display.
* **Keyboard Support:** The calculator display also accepts keyboard input, and the Enter key triggers the calculation.

## How to Use

1.  Open the `index.html` file in any web browser.
2.  Use the on-screen buttons to input numbers and select operations.
3.  The result will be displayed in the calculator's display area.
4.  You can also use your keyboard to enter numbers and operators.
5.  Press the "Enter" key to calculate the result.
6.  Press the "C" button to clear the display.
7.  Press the "←" button to delete the last entered character.

## Technologies Used

* HTML:  For the structure of the calculator interface.
* CSS (Internal):  For the styling of the calculator (embedded within the `index.html` file).
* JavaScript (Internal):  For the calculator's logic and functionality (embedded within the `index.html` file).

## Installation (Not Applicable)

This is a client-side web application and does not require any installation. Simply download or clone the repository and open the `index.html` file in your browser.

## Contributing

Contributions are welcome! If you find any bugs, have suggestions for improvements, or want to add new features, please feel free to:

1.  Fork the repository.
2.  Create a new branch for your changes (`git checkout -b feature/your-feature` or `git checkout -b bugfix/your-bug`).
3.  Make your changes and commit them (`git commit -am 'Add some feature'`).
4.  Push to the branch (`git push origin feature/your-feature`).
5.  Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
## Author

Tarun Teja
---

**Explanation of Key Improvements and Why They're Important:**

* **More Detailed Features:** The "Features" section now accurately reflects the capabilities of your calculator based on the code.  It explicitly mentions parentheses, clear/backspace functionality, and the specific trigonometric functions implemented.
* **Clearer Instructions:** The "How to Use" section is expanded to guide users on how to use the backspace, clear, and keyboard input features.
* **Emphasis on Internal CSS/JS:** The "Technologies Used" section explicitly states that the CSS and JavaScript are internal (within the HTML file), which is accurate for your code.
* **License Information:** I've included a placeholder for license information.  It's highly recommended to choose an open-source license (like the MIT License, which I've used as an example) to clearly define how others can use your code.  If you don't want to use a license, you can remove this section.
* **Contribution Guidelines:** The "Contributing" section provides a standard set of steps for others to contribute to your project, which is good practice for open-source projects.

**How to Add the License (If You Choose One):**

1.  **Choose a License:** If you want to use the MIT License (or another license), you can find the full text of the license online (e.g., search for "MIT License text").
2.  **Create a `LICENSE` File:** Create a new file in your repository's root directory named `LICENSE` (all uppercase, no extension).
3.  **Copy the License Text:** Copy the full text of the license you chose into the `LICENSE` file.
4.  **Commit and Push:** Add, commit, and push the `LICENSE` file to your repository.
5.  **Update README (Already Done):** The README I provided already includes a link and badge for the MIT License. If you use a different license, update the link and badge accordingly.  You can find license badges (like the one I included) on sites like shields.io.

