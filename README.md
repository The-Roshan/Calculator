# 3D Animated Calculator

## Overview
The 3D Animated Calculator is a web-based application built with HTML, CSS, and JavaScript, designed to provide a visually appealing and functional calculator with a 3D aesthetic. It supports basic arithmetic operations, percentage calculations, and includes features like clearing the display and deleting the last input. The calculator is responsive and user-friendly, suitable for both desktop and mobile devices.

## Features
- **Calculator Interface**: A clean layout with a display input and a grid of buttons for numbers, operators, and functions.
- **Functionality**:
  - Basic operations: Addition (+), Subtraction (-), Multiplication (*), Division (/).
  - Percentage (%) calculations.
  - Clear (C) button to reset the display.
  - Delete (DEL) button to remove the last character.
  - Equals (=) button to compute results.
- **3D Styling**: Buttons and the calculator body feature 3D effects using CSS (e.g., shadows, hover animations).
- **Responsive Design**: Optimized for various screen sizes via CSS media queries.
- **Interactive Buttons**: Clickable buttons with JavaScript-driven functionality for real-time calculations.

## Tech Stack
- **HTML5**: Structure of the calculator interface.
- **CSS3**: Styling, including 3D effects and responsiveness (`styles.css`).
- **JavaScript**: Logic for calculator operations and button interactions (`script.js`).

## Project Structure
```
3d-calculator/
├── index.html         # Main HTML file
├── styles.css        # CSS styles for 3D effects and layout
├── script.js         # JavaScript for calculator logic
├── LICENSE.md        # MIT License
└── README.md         # This file
```

## Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge).
- A code editor (e.g., VS Code) for customization.

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/The-Roshan/calculator.git
cd 3d-calculator
```

### 2. Open the Website
- Open `index.html` in a web browser:
  ```bash
  open index.html  # macOS
  start index.html  # Windows
  ```
- Alternatively, use a local development server (e.g., VS Code Live Server) for a better experience.

### 3. Customize (Optional)
- Edit `styles.css` to modify colors, 3D effects, or button styles.
- Update `script.js` to add advanced calculator features (e.g., scientific functions).
- Modify `index.html` to adjust the layout or add new buttons.

## Usage
1. **Input Numbers**: Click number buttons (0-9) to enter digits.
2. **Operators**: Use operator buttons (+, -, *, /, %) to build expressions.
3. **Calculate**: Press the equals (=) button to compute the result.
4. **Clear/Reset**: Use the C button to clear the display or DEL to remove the last character.
5. **Responsive**: Access the calculator on mobile or desktop for consistent functionality.

## Deployment
- **Static Hosting**:
  1. Upload `index.html`, `styles.css`, and `script.js` to a hosting service (e.g., GitHub Pages, Netlify, Vercel).
  2. Configure the service to serve `index.html` as the entry point.
- **Netlify Example**:
  1. Drag the project folder into Netlify’s dashboard.
  2. Deploy and access the live URL provided.
- **Local Server**:
  ```bash
  python -m http.server 8000
  ```
  Open `http://localhost:8000` in a browser.

## Notes
- **JavaScript Logic**: The `script.js` file must implement functions like `append()`, `clearDisplay()`, `deleteLast()`, and `calculate()` for full functionality.
- **Styling**: The `styles.css` file should include 3D effects (e.g., box-shadow, transform) for buttons and the calculator body.
- **Enhancements**: Consider adding keyboard input support or advanced operations (e.g., square root, exponents).
- **SEO**: Update meta tags in `<head>` (e.g., `description`, `keywords`) for better visibility.

## License
This project is licensed under the MIT License. See `LICENSE.md` for details.

## Contributing
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Commit changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## Acknowledgments
- Built with vanilla HTML, CSS, and JavaScript for educational purposes.
- Inspired by modern web calculator designs with 3D aesthetics.

## Contact
For questions or feedback, open an issue on GitHub or contact The-Roshan.
