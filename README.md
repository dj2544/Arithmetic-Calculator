# 🧮 Tkinter Calculator

A simple calculator GUI application built using Python's `tkinter` library. This app allows basic arithmetic operations such as addition, subtraction, multiplication, division, and exponentiation.

---

## 🚀 Features

- Basic arithmetic operations: `+`, `-`, `*`, `/`, and exponentiation using `x` (press twice: `xx`)
- Buttons for digits, operations, parentheses, and decimal point
- Clear (`C`) and All Clear (`AC`) functionality
- Equation result display using `=`
- Responsive GUI layout with a consistent button spacing
- Informational labels for user instructions

---

## 📐 UI Layout

- **Button Dimensions**:
  - Height: `1`
  - Width: `3` (or `(height * 2) + 1`)
- **Button Font Size**: `9`
- **Spacing**:
  - Vertical (rows): `60 pixels`
  - Horizontal (columns): `60 pixels`
- **Window Size**: `250 x 500 px`
- **Colors**:
  - Background: `LightCyan2`
  - Number Buttons: `Gold`
  - Operator Buttons: `DarkOrange`
  - Special Buttons (`=`, `C`, `AC`, `Ok`): `Blue`, `OrangeRed`, `Red`, `CadetBlue`

---

## ⚙️ How It Works

1. **Input**: Users enter mathematical expressions using the buttons.
2. **Evaluation**: Pressing `=` uses Python’s `eval()` to compute the result.
3. **Error Handling**: Invalid expressions trigger a popup via `tkinter.messagebox`.
4. **Additional Controls**:
   - `C`: Removes the last character
   - `AC`: Clears the entire expression
   - `Ok`: Closes the calculator

---

## 🧩 Dependencies

- Python 3.x
- `tkinter` (bundled with standard Python installation)

---

## ▶️ Running the App

1. Save the code to a file named `calculator.py`
2. Open a terminal and run:

```bash
python calculator.py
