# React Calculator

A simple and accessible calculator built with React, supporting input via mouse and keyboard, operation history, and validations to avoid common errors.

---

## Features

- Basic operations: addition, subtraction, multiplication, and division.
- Input via buttons (mouse) and keyboard (numbers, operators, and Enter to calculate).
- Validations to prevent consecutive repeated operators.
- Negative sign (`-`) allowed at the start of the operation.
- Prevents division, multiplication, and decimal comma at the beginning.
- Supports long numbers with horizontal scroll in the display.
- Operation history displayed and persisted via localStorage.
- Accessibility: visible focus, keyboard navigation, and `aria-label`s.

---

## Technologies

- React (hooks and Context API)
- CSS (Tailwind CSS)
- localStorage for history persistence
