# Calculator

A lightweight web-based calculator (version 1.1.2).

`index.html` is the latest version of the interface in this repository - simply open it directly to use the calculator.

## Features
- Basic arithmetic operations: addition, subtraction, multiplication, division
- Decimal number support
- Clear/Delete (CE / Backspace)
- Calculation history: view and load past calculation results (up to 10 records)
- **History toggle**: one-click to show/hide history panel
- **Clear History**: one-click to clear all calculation history
- **Local storage**: history and language preferences are automatically saved locally
- **Multiple background themes**: 6 gradient background themes, click the theme button to switch
- **Language switching**: toggle between Chinese and English interface
- **Keyboard support**: support keyboard input for numbers, operators and control keys
- **Smooth button animations**:
  - Hover effect with lift and scale animation
  - Multi-layered shadows for enhanced depth
  - Press feedback when clicked
  - Ripple effect spreading from the center
- **Mouse-following highlight**: radial gradient highlight at mouse position when hovering, enhancing interaction experience
- Clean responsive interface that works on desktop and mobile devices

## Quick Start
1. Clone the repository or download ZIP:
   ```bash
   git clone https://github.com/JiangWanZhengChouYv/Calculator.git
   ```
2. Open `index.html` directly locally (double-click or open the file in a browser).
   - If you use a static site server (recommended for some browser permission restrictions):
     ```bash
     # Use Python 3 to quickly start a static server (in the repository root directory)
     python -m http.server 8000
     # Then open http://localhost:8000/index.html in your browser
     ```
3. Open webpage
   - Directly enter in the browser address bar:
     ```
     jiangwanzhengchouyv.github.io/Calculator
     ```
## Supported Browsers
- Modern browsers: Chrome, Firefox, Edge, Safari (older browsers may have differences in some ES/HTML features)

## File Structure (Brief)
- index.html — Main interface (open directly to run)
- 历史版本/ — Contains backup files for Cal1.1.2, Cal1.1.0, Cal1.0.4, Cal1.0.0
- README.md — Project documentation (Chinese version)
- README_EN.md — Project documentation (English version)

## Contributing
Issues and PRs are welcome:
- For bug reports, please describe the reproduction steps, browser and version information.
- For new feature suggestions, please describe the expected behavior and use cases.

## License
This project uses the MIT license.

## Author
JiangWanZhengChouYv

## Version History
- 1.1.2 — Added Chinese/English language switching function
- 1.1.1 — Added clear history function
- 1.1.0 — Added multiple background theme switching function
- 1.0.4 — Fixed issue with history text exceeding boundaries
- 1.0.3 — Redesigned button layout, placed operator buttons in one row for better layout
- 1.0.2 — Optimized interface layout, history panel displayed by default with responsive layout
- 1.0.1 — Added history function, support viewing and loading past calculation records
- 1.0.0 — Initial version (with basic calculation functions)
