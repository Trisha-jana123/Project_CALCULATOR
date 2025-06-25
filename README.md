# 🔢 React Calculator App

This is a simple and clean **calculator UI built using React**, focused on learning **component structure**, **modular CSS**, and UI layout. The app includes a display and number pad arranged with responsive styling using **CSS Modules**.

---

## 🚀 Tech Stack

- ⚛️ **React** – Component-based architecture
- 🎨 **CSS Modules** – Scoped styling for each component
- 🧠 **JavaScript Logic** – Simple in-component state handling

---

## 📁 Project Structure
src/
│
├── components/ # Core functional components
│ ├── ButtonsContainer.jsx # Main layout that uses Display + ButtonsContainer
│ ├── ButtonsContainer.modules.css # Output screen
│ ├── Display.jsx # Grid of calculator buttonsstyles/ # All CSS Modules for scoped styling
│ ├── Display.module.css # Styling for Calculator container
│
├── App.jsx # Entry React component, renders <Calculator />
├── App.module.css # ReactDOM entry point
└── main.jsx # Optional global CSS (e.g., resets, fonts)


---

## ✨ Features

- 🖥 **Clean Calculator Layout** — Split into Display and Buttons
- 🎨 **Styled with CSS Modules** — Local styles for each part
- 🎯 **Centered on Screen** — Layout is vertically and horizontally centered
- 📱 **Responsive Button Grid** — Grid layout ensures exactly 3 buttons per row
- 👩‍🎓 **Learning-Focused** — Built without extra libraries for maximum clarity

---

## 📦 Installation & Running

1. Clone the repo:

```bash
git clone https://github.com/your-username/react-calculator.git
cd react-calculator
npm install
npm run dev
Now open http://localhost:5173/ in your browser to view the calculator.
```

What I Learned
This project helped me practice:

1. How to build a UI with reusable components

2. Managing state for calculator logic using useState

3. Centering layouts and button grid design

4. Applying local styles using CSS Modules

5. Structuring a small project cleanly and modularly





