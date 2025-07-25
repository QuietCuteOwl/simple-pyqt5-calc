# Calculator

This is a basic calculator built using Python.
The evaluation is done using a custom parser which implements the shunting yard algorhythm to evaluate.

### Core Features:
- The GUI is built using Tkinter.
- Arithmetic operator buttons include: `+`, `-`, `*`, `/`, `^` and `=`.
- Additional buttons include: `C` (clear_last), `AC` (clear_all), and `.` (decimal point).
- The display is a `tkinter.entry` widget that shows the current expression or result.

### Input Handling:
- When a button is clicked, or a key is pressed, its value is processed by the `validate()` method in `input_handling.py`.
- Everything is stored in one str called `self.expr`.
- Operator verification prevents invalid sequences like multiple operators in a row.
- When `=` is pressed, the expression is evaluated using a custom built parser which has a tokenizer and implements 
  the `Shunting Yard` algorhythm to calculate the expression.

___
## About Me

2.5 months into learning python which is also my first language.I am learning as I go.

___
## Features
- Add, subtract, multiply, divide, exponentiation
- Clear all button, Clear last button
- Parentheses
- Easy to use

___
## Future Plans
- Add support for roots and logs
- Improve the UI layout and styling

___
## Requirements
- Python 3.8 or higher

___
## Run the App
Make sure you have Python 3 installed. Then run:

```bash
python calculator_manager.py
```
