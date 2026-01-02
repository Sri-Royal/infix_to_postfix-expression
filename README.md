# 🔄 Infix to Postfix Expression Visualizer

##  Overview
This project is a **web-based Infix to Postfix Expression Visualizer** built using **HTML, CSS, and JavaScript**.  
It converts a **space-separated infix expression** into a postfix expression using a **stack-based algorithm** and shows the conversion **step by step**.

This project helps students clearly understand **stack operations**, **operator precedence**, and **expression conversion**.

---

##  Features
- Supports **space-separated operands**
- Handles **multi-digit numbers** and **variables**
- Validates infix expressions before conversion
- Step-by-step visualization
- Stack contents displayed at each step
- Next and Previous step navigation
- Beginner-friendly user interface

---

##  Concepts Used
- Stack Data Structure
- Infix to Postfix Conversion
- Operator Precedence
- Expression Validation
- JavaScript DOM Manipulation

---

## 🧪 Sample Inputs:

### ✅ Valid Inputs
examples:A + B * C
( A + B ) * C
10 + 20 * 3
A * ( B + C ) - D
outputs:
A + * B
( A + B
A B +

---

## ⚙️ Algorithm Explanation
1. Read the infix expression token by token (space-separated).
2. If the token is an **operand**, add it to the postfix expression.
3. If the token is `'('`, push it onto the stack.
4. If the token is `')'`, pop operators until `'('` is found.
5. If the token is an **operator**, pop operators based on precedence.
6. Push the current operator onto the stack.
7. After all tokens are processed, pop remaining operators from the stack.
8. Display each step visually.

---

##  Technologies Used
- **HTML** – Structure
- **CSS** – Styling and layout
- **JavaScript** – Logic and visualization

---

## 📁 Project Structure
infix-to-postfix-visualizer/
├── infix_to_postfix-expression.html
├── infix_to_postfix-expression.css
├── infix_to_postfix-expression.js
└── README.md
