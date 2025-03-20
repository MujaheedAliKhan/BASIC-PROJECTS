# Basic Calculator

This project is a simple web-based calculator that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. It is built using HTML, CSS, and JavaScript.

## Features
- **Responsive Design:** Works on different screen sizes and devices.
- **Basic Operations:** Supports addition, subtraction, multiplication, and division.
- **Clear Functionality:** Includes options to clear the display (`AC`) or delete the last input (`C`).
- **Evaluate Expressions:** Handles numerical expressions with multiple operators.

## Project Structure
The project consists of the following files:

- **index.html:** Contains the HTML structure for the calculator.
- **style.css:** Defines the styling and layout of the calculator.
- **script.js:** Includes the logic for handling button clicks and evaluating expressions.

## How to Use
1. Open the `index.html` file in a web browser.
2. Use the buttons to input numbers and operators into the display.
3. Press `=` to evaluate the expression.
4. Use `AC` to clear the entire display or `C` to delete the last character.

## Code Explanation
### HTML
- The calculator is created using a `<form>` element with multiple `<input>` buttons for numbers, operators, and actions.
- A text input field is used as the display.

### CSS
- Styling is applied using an external stylesheet (`style.css`) to make the calculator visually appealing and user-friendly.

### JavaScript
- Inline `onclick` events are used to handle button interactions.
- The `eval()` function is used to evaluate the entered expressions when `=` is pressed.

## Example
### Input:
```
12 + 8
```
### Output:
```
20
```
## Installation & Usage
### Run Locally
-Clone the repository

-git clone 

Navigate to the project folder

```bash
 cd 
```
## Use Calculator through Online

This is a link to [Basic calculator](http://127.0.0.1:5500/BASIC-PROJECTS/BASIC-CALCULATOR/index.html)

## Note
For security reasons, avoid using `eval()` in production applications as it can execute arbitrary code. Consider using a safer alternative for evaluating mathematical expressions.

## License
This project is open-source and available under the MIT License.

## Contributions
Feel free to fork this repository and contribute by submitting pull requests. Suggestions and improvements are welcome!

---
## Author
- Lavani Mujaheed Ali Khan

**Enjoy using this Basic Calculator!** 🚀

