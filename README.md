# Pure React Project

This project is a **minimal React setup** built without any bundlers, transpilers, or frameworks.  
It uses plain **HTML + JavaScript** with React and ReactDOM loaded from a CDN.

## About

The project demonstrates how React works at its core:
- A `div` with `id="root"` serves as the mounting point.
- React and ReactDOM are imported via `<script>` tags from [unpkg](https://unpkg.com/).
- Components are created with `React.createElement` (without JSX).
- The app is rendered into the DOM using `ReactDOM.createRoot(...).render(...)`.

This setup is useful for **learning React fundamentals** without extra tooling like Create React App, Vite, or Webpack.

## 📂 Project Structure

├── index.html # Main entry point  
├── README.md # Project documentation

## ▶️ How to Run

1. Clone or download this repository.
2. Open index.html in your browser (no server required).
3. You should see "Hello Pure React!" rendered on the page.

Just in case you're using github codespaces, you can run the following command in the terminal:
```
python3 -m http.server 5500
```

---
