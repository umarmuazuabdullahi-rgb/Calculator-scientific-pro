# Scientific Calculator Pro

A modern, responsive, and customizable single-page calculator application built with clean HTML5, CSS3 (using CSS variables), and vanilla JavaScript. Designed to function smoothly on both mobile and desktop screens.

---

## Features

- **Dual Keypad Modes**: 
  - **Scientific Mode**: Contains advanced mathematical operators including trigonometric functions, logarithms, powers, roots, factorials, percentages, Permutations ($nPr$), and Combinations ($nCr$).
  - **Basic Mode**: A simplified layout featuring classic addition, subtraction, multiplication, and division keys for quick daily tasks.
- **Customization Settings**:
  - **Themes**: Switch smoothly between **Dark Theme**, **Light Theme**, and **OLED Black**.
  - **Haptic Feedback**: Optional key vibration on tap (supported on compatible mobile browsers).
  - **Decimal Precision**: Configure the decimal precision length (ranging from 4 to 12 decimal places).
- **Navigation & Editing**: Move the cursor using the navigation arrows (`◀` / `▶`) and make precise inline corrections using the `DEL` (Delete) key.
- **Persistent Calculation History**: Keeps track of previous calculations. Users can tap on any past result to load it back into the main input screen or clear the history log with one tap.
- **Advanced Memory**: Supports standard memory actions (`MS`, `MR`, `M+`, `M-`) with status indicators shown at the top of the keypad.
- **Keyboard Support**: Integrated physical keyboard support for rapid calculations using number pads and hotkeys.

---

## Getting Started / Installation

This application is fully standalone and offline-capable. It does not require any external dependencies, frameworks, or internet connection to function.

### How to Run:
1. Download or copy the code from your main HTML file (e.g., `index.html`).
2. Double-click the file to open it in any modern web browser (Chrome, Firefox, Safari, Edge, etc.).
3. (Optional) You can host this file on platforms like GitHub Pages, Vercel, or Netlify with zero configuration.

---

## How to Use

### 1. Mode Selection
To switch between **Basic** and **Scientific** modes:
- Open the sidebar menu by tapping the **Menu Icon** (`☰`) in the top left corner.
- Choose your preferred mode under the **Mode** section.

### 2. Shift Operations
Some keys have double functions indicated by small gold labels above them:
- Press the `SHIFT` button to toggle secondary operations.
- For example, pressing `SHIFT` followed by `Sin` will evaluate inverse sine (`asin`).

### 3. Settings Configuration
To adjust your workspace preferences:
- Open the sidebar menu (`☰`).
- Select **Settings** (`⚙️`) to toggle haptic vibration, select a theme, or adjust decimal output precision.

### 4. Desktop Keyboard Shortcuts
The following physical keyboard mappings are supported:
- **Numbers (0-9)**: Inputs corresponding digits.
- **Operations (`+`, `-`, `*`, `/`)**: Inputs standard operational symbols.
- **`Enter` or `=`**: Evaluates the input expression.
- **`Backspace`**: Deletes the character before the cursor.
- **`Escape`**: Clears the entire display.
- **`Left Arrow` / `Right Arrow`**: Moves the navigation cursor.

---

## File Structure
```text
├── index.html       # Combined Single-Page Application (HTML, CSS, JS)
└── README.md        # Documentation and guide
