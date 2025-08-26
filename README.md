# Simple Calculator

A basic, single-page HTML calculator with essential arithmetic operations.

## Features
- Addition, Subtraction, Multiplication, Division
- Decimal point support
- Clear (C) button
- Error handling for division by zero
- Left-to-right evaluation for chained operations (e.g., `2 + 3 * 2` will calculate `(2+3) * 2 = 10`)

## Usage
1. Save the `index.html` file to your computer.
2. Open `index.html` in any modern web browser.
3. Use the buttons to perform calculations.

## Test Cases
This calculator includes embedded JavaScript test cases that run automatically when the page loads. Open your browser's developer console (usually F12) to view the test results. Each test will log whether it passed or failed, along with expected and actual values.

## Code Structure
- **HTML**: Defines the calculator layout (display and buttons).
- **CSS**: Provides minimal styling for a clean and functional appearance.
- **JavaScript**: Handles all calculator logic, including button clicks, display updates, and arithmetic operations using `eval()` for simplicity. Includes self-checking test cases.

## Notes
- The `eval()` function is used for performing calculations. While generally discouraged for security reasons in applications handling untrusted user input, it is acceptable for this simple, self-contained client-side calculator where input is strictly controlled by button presses.
- The calculator follows a common simple calculator logic where operations are performed in the order they are entered, rather than mathematical operator precedence (e.g., `2 + 3 * 2` results in `10`, not `8`).