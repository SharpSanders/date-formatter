# Date Formatter

A responsive JavaScript utility that formats the current date into multiple display styles.

Built to demonstrate working with the JavaScript `Date` object, dynamic DOM updates, and user-driven formatting logic.

## Live Demo
https://sharpsanders.github.io/date-formatter/

![Date Formatter Screenshot](./img/Screenshot-date-formatter.png)

---

## Features

- Automatically displays today’s date on page load
- Switch between multiple formats:
  - `DD-MM-YYYY` (default)
  - `YYYY-MM-DD`
  - `MM-DD-YYYY HH:MM`
- Real-time UI updates based on user selection
- Clean, responsive layout
- Lightweight — no frameworks or libraries

---

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)

---

## Concepts Demonstrated

- Using the JavaScript `Date()` object
- Extracting:
  - Day
  - Month
  - Year
  - Hours
  - Minutes
- Formatting date strings with padding logic
- Event-driven DOM updates
- Responsive UI design

---

## How It Works

1. The app initializes the current date using `new Date()`.
2. Individual date components are extracted.
3. A format option is selected via dropdown.
4. The selected format dynamically updates the rendered output.

All formatting is handled client-side using pure JavaScript.

---

## Project Structure

date-formatter/
├── index.html
├── styles.css
├── script.js
└── img/
└── Screenshot-date-formatter.png


---

## What I Practiced

- Working with built-in browser date APIs
- Formatting and padding values for consistent display
- Updating UI state from dropdown input
- Writing clean, modular JavaScript logic

---

Built by Trevyn Sanders  
GitHub: https://github.com/SharpSanders