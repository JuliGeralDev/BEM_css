# 🧱 BEM CSS Project – Modular CSS Architecture Demo

This project demonstrates the use of **BEM (Block Element Modifier)** methodology for structuring CSS in a clean and maintainable way. It features a simple product listing page styled with modular CSS files and follows modern front-end best practices.

> ⚠️ Note: This is a front-end focused static website built with HTML5 and CSS3.

## 🔗 Live Preview

[👉 View the Demo on Netlify](https://bemcss-juligeraldev.netlify.app/)
## ✨ Features

- **BEM Methodology** – Structured CSS with clear class naming:  
  - Block: `.productos`  
  - Element: `.productos__heading`, `.producto__nombre`  
  - Modifier: `.producto__precio--oferta`

- **Responsive Design** – Uses media queries to adapt the layout for desktop, tablet, and mobile views

- **CSS Variables** – Global colors, fonts, and reusable values defined in `styles.css`

## 📁 Project Structure

BEM_css/  
├── css/  
│   ├── normalize.css       # CSS reset for cross-browser consistency  
│   ├── styles.css          # Global styles and utility variables  
│   ├── productos.css       # Product section styled with BEM methodology  
├── img/                    # Product images (not included in this repo)  
├── index.html              # Main HTML file  
└── README.md               # Project documentation

## 📄 Files Overview

- **normalize.css** – CSS reset for consistent base styles  
- **styles.css** – Global styles including font imports, colors, layout helpers  
- **productos.css** – BEM-based styles for the product listing grid  
- **index.html** – Main structure of the web page using semantic HTML5  

## 📐 How to Use

1. Clone or download the repository  
2. Place the folder in your local server environment (e.g., `htdocs` for XAMPP)  
3. Open `index.html` in your browser to see the layout in action  

## 🔤 Dependencies

- **Google Fonts** – The project uses the "Raleway" font from Google Fonts

## 👩‍💻 Author

Juliana García Corredor  
GitHub: [@JuliGeralDev](https://github.com/JuliGeralDev)

