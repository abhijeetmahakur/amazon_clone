# Amazon Storefront Clone

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-FF9900?style=for-the-badge&logo=amazon&logoColor=white)](https://abhijeetmahakur.github.io/amazon_clone/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%20Modules-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-Flexbox%20%26%20Grid-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

A responsive, pixel-accurate web recreation of the Amazon e-commerce storefront. Features an automatic hero image slider with directional controls, off-canvas navigation drawer, dynamic 'Today's Deals' carousel powered by ES6 modules, and a modern shopping layout.

---

## 🚀 Download & Live Demo

### 🌐 1. Try Live in Your Browser
Explore the storefront directly on GitHub Pages:  
👉 **[Open Live Amazon Clone Demo](https://abhijeetmahakur.github.io/amazon_clone/)**

### 💻 2. Run Locally on Windows
Because this project utilizes modern JavaScript ES6 modules (`import/export`), it should be served via an HTTP server rather than loaded directly as a local file:

```powershell
# Clone the repository
git clone https://github.com/abhijeetmahakur/amazon_clone.git
cd amazon_clone

# Option A: Run using Python built-in server
python -m http.server 8000
# Open http://localhost:8000 in your browser

# Option B: Run using Node.js
npm start
```

---

## 📸 Screenshots & UI Showcase

<!--
  PLACEHOLDER INSTRUCTION:
  1. Open https://abhijeetmahakur.github.io/amazon_clone/ or http://localhost:8000.
  2. Capture screenshots of the top navigation bar, active hero carousel, and today's deals grid.
  3. Save the screenshots in an `assets/` folder as `storefront_view.png`.
-->

| Hero Carousel & Product Categories | 'Today's Deals' Horizontal Scroller |
| :---: | :---: |
| ![Amazon Storefront Screenshot](https://placehold.co/600x380/131921/FF9900?text=Amazon+Clone+Hero+Slider+Screenshot) | ![Amazon Deals Carousel](https://placehold.co/600x380/232F3E/FFFFFF?text=Today's+Deals+Horizontal+Scroller) |
| *Multi-panel header, search categorization, and auto-cycling promotional banner* | *Dynamic product card injection with discount badge percentages and pagination* |

---

## ✨ Key Features

- **Automated Hero Banner Slider:** Auto-advancing promotional banner with interactive left/right transition controls.
- **Dynamic 'Today's Deals' Scroller:** Data-driven product cards imported via ES6 modules with horizontal scrolling pagination.
- **Off-Canvas Slide-In Drawer:** Smooth animated hamburger navigation drawer menu for category filtering.
- **Search & Filter Header:** Amazon-style search bar with category dropdown selection, language selector, and returns indicator.
- **Responsive Category Cards:** Four-column grid cards showcasing deals across electronics, home decor, fashion, and groceries.
- **Interactive Cart Counter:** Real-time cart state badge element ready for shopping cart integrations.

---

## 🛠 Tech Stack

| Technology | Role |
| :--- | :--- |
| **HTML5** | Semantic web layout, accessible navigation structures, product containers |
| **CSS3** | Flexbox, CSS Grid, media queries, keyframe transitions, and custom hover states |
| **JavaScript (ES6+)** | Carousel slider logic, modular data imports (`todayDeal.js`), DOM event listeners |
| **Font Awesome** | High-resolution SVG shopping and control vector icons |
| **GitHub Pages** | Static hosting with automated continuous deployment |

---

## 📂 Project Structure

```
amazon_clone/
├── .github/
│   └── workflows/
│       └── deploy-pages.yml     # Automated GitHub Pages CI/CD workflow
├── index.html                   # Main storefront markup and product grids
├── style.css                    # Complete CSS stylesheet (layout, header, cards)
├── javascript.js                # Core UI scripts (carousel, sidebar, deals logic)
├── todayDeal.js                 # Modular product dataset for deals section
├── package.json                 # Optional npm scripts definition
├── .gitignore                   # Ignored temporary, node, and editor files
├── LICENSE                      # MIT License
└── README.md                    # Project documentation
```

---

## 🗺 Roadmap

- [ ] Interactive shopping cart modal with local storage persistence
- [ ] Product details view modal with zoomable thumbnail gallery
- [ ] Search query filtering across deal items
- [ ] Mock checkout flow with order summary calculation

---

## 👨‍💻 Author

**Abhijeet Mahakur**
- GitHub: [@abhijeetmahakur](https://github.com/abhijeetmahakur)
- LinkedIn: [Abhijeet Mahakur](https://www.linkedin.com/in/abhijeetmahakur/)
- Location: Bhubaneswar, India

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - Copyright (c) 2026 Abhijeet Mahakur.  
*Disclaimer: This is an educational personal showcase project and is not affiliated with Amazon.com, Inc.*