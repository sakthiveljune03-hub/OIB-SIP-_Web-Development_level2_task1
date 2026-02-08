# Simple Calculator

A lightweight, user-friendly web-based calculator built with HTML, CSS, and JavaScript.

## Features

- **Basic Arithmetic Operations**: Supports addition (+), subtraction (-), multiplication (*), and division (/)
- **Clean UI**: Modern dark-themed interface with an intuitive button layout
- **Clear Function**: AC (All Clear) button to reset the calculator
- **Error Handling**: Catches invalid expressions and displays error messages
- **Responsive Design**: Centered layout that works on different screen sizes

## How to Use

1. Open the `index.html` file in your web browser
2. Click number and operator buttons to build your expression
3. Click the `=` button to calculate the result
4. Click `AC` to clear and start a new calculation

## Technical Details

### HTML Structure
- Input field for displaying the current expression and result
- Grid-based button layout (4 columns)
- Special styling for the 0 button (spans 2 columns) and equals button (orange, spans 2 columns)

### CSS Styling
- **Body**: Flexbox layout for center alignment with light gray background
- **Calculator**: Dark background (#222) with rounded corners and padding
- **Buttons**: Grid layout with 10px gaps
- **Display**: Right-aligned text input with 50px height

### JavaScript Functionality
- Event listeners on all buttons for click events
- Expression building on number/operator clicks
- Expression evaluation using `eval()` on equals click
- Error handling with try-catch block
- Clear functionality with AC button

## Project Files

- `index.html` - Main HTML file containing structure, styles, and script

## Browser Compatibility

Works on all modern browsers that support ES6 JavaScript (Chrome, Firefox, Safari, Edge)

## Future Improvements

- Add decimal point (.) functionality
- Add more advanced operations (square root, percentage, etc.)
- Implement keyboard input support
- Add operation history
- Improve error handling for edge cases

---

**Created**: February 2026