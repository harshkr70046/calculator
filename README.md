# 🧮 JavaScript Calculator
<a href="https://harshkr70046.github.io/calculator/">click here</a>

This is a simple calculator built using HTML, CSS, and JavaScript. It performs basic arithmetic operations like addition, subtraction, multiplication, and division. The core logic is handled using JavaScript's `eval()` function.

## 🔧 Features

- Basic arithmetic operations (+, −, ×, ÷)
- Clear screen (C button)
- Real-time input display
- Evaluates expressions using JavaScript's built-in `eval()` function

---

## 🛠️ How It Works

### 1. HTML Structure

The calculator is made up of:
- A **display** to show the current input and result.
- A set of **buttons** representing digits (0-9), operators (+, -, *, /), a clear button (`C`), and an equals button (`=`).

### 2. CSS Styling

Basic CSS is used to:
- Arrange buttons in a grid layout
- Style the calculator for a clean, modern look
- Add hover and active states for better user interaction

### 3. JavaScript Logic

Here's how the calculator works step-by-step:

#### Step 1: Selecting Elements

```js
const display = document.getElementById("display");
const buttons = document.querySelectorAll("button");
