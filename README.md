# Product Gallery with CSS-Only Filter System

## 📋 Project Overview
This project is a **Product Gallery webpage** for an e-commerce store, developed as part of a **Full Stack Development assignment**. The page allows users to filter products by category using **pure CSS** — without any JavaScript. The layout utilizes **Flexbox**, **CSS Grid**, **Media Queries**, and **Advanced CSS Selectors** to ensure responsiveness and interactivity.

## 🎯 Features

### 🧭 Header & Navigation
- Store name displayed on the left.
- Navigation links aligned to the right.
- A fully styled search bar implemented using CSS.

### 🧩 Filter Sidebar
- Sidebar positioned on the left in desktop view.
- Contains category filters such as:
  - Electronics
  - Clothing
  - Books
- Uses **radio buttons** or **checkboxes** for category selection.
- Filtering behavior achieved entirely with **CSS selectors** like `:checked`, `:not()`, and sibling combinators.

### 🛍️ Product Grid
- Displays at least **12 product cards**.
- Each card includes:
  - Product image
  - Product title
  - Price
  - "Add to Cart" button
- Responsive layout:
  - **4 products per row** on desktop.
  - **2 products per row** on tablet.
  - **1 product per row** on mobile.

### 🎨 CSS-Only Filter Functionality
- No JavaScript used.
- When a category is selected, only products from that category remain visible.
- Implemented using creative CSS combinations like:
  ```css
  input[type="radio"]:checked ~ .product-grid .product:not(.selected-category) {
      display: none;
  }
  ```

### 📱 Responsive Design
- Fully responsive using **media queries**.
- Sidebar repositions to the top for smaller screens.
- Smooth grid adaptation across breakpoints.

## 🧠 Key Concepts Applied
- **Dropdowns** — for category and search-related features.
- **Flexbox** — for aligning navigation and header elements.
- **Grid** — for the responsive product layout.
- **Media Queries** — for adapting layout to different screen sizes.
- **Advanced Selectors** — for implementing interactivity without JavaScript.

## ⚙️ Technologies Used
- HTML5
- CSS3 (Flexbox, Grid, Media Queries)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/MeesamBukhari/FSD-A1-Product-Gallery.git
   ```
2. Open the `index.html` file in your preferred browser.

## 🧩 Future Enhancements
- Add JavaScript-based filtering for enhanced interactivity.
- Integrate backend for real-time product data.
- Add animations and transitions for smoother UI.

## 📚 Author
**Meesam Bukhari**  
Front-End Web Developer | Level 2 Seller @ Fiverr  
[GitHub Profile](https://github.com/MeesamBukhari)

---
⭐ If you found this project helpful, consider giving it a star on GitHub!

