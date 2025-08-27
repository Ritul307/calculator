# 🧮 Basic Calculator

A simple and stylish web-based calculator built using **HTML, CSS, and JavaScript**.  
It supports basic arithmetic operations like addition, subtraction, multiplication, and division, with a modern UI.

---

## 🚀 Features
- Clean, responsive UI with **neumorphism effect** ✨  
- Basic operations: `+`, `-`, `*`, `/`  
- Special buttons:
  - **AC** → Clear all input  
  - **DE** → Delete the last character  
  - **=** → Evaluate the expression  
- Hover effects for interactive buttons  
- Large, easy-to-read display  

---

## 📂Important elements I used in css:

<form> → Holds all the calculator inputs.
<input type="text"> → Display area (shows numbers & results).
<input type="button"> → All calculator buttons (0–9, +, -, *, /, =, AC, DE).
<div> → For grouping display and button rows.
CSS (Styling in your project)
Used to style the calculator and make it look modern.
Important CSS features you used:
flexbox → To center the calculator (display: flex; align-items: center; justify-content: center;).
box-shadow → For 3D neumorphic button effect.
border-radius → Rounded corners.
hover effects → Buttons change color slightly when hovered.
font-size & colors → Big white text on dark background.

**JavaScript (Logic in your project)**

Used inline JavaScript inside HTML with onclick attributes.
Important functionality you implemented:
AC button → Clears display (calc.display.value = '').
DE button → Deletes last character (slice(0, -1)).
Numbers & Operators → Append values to display (+=).
Equal button (=) → Uses eval() to calculate result.


My website https://ritul307.github.io/calculator/
