
# CSS Practice – The `position` Property

This project includes several small exercises to practice and master the use of the CSS `position` property. Each task focuses on a different concept: centering, sticky menus, tooltips, and scroll-based behavior.

---

## 🟦 TP 1: Center a Box in the Screen

### 🎯 Objective
Create a square box of 200x200 pixels and center it **both vertically and horizontally** in the browser window.

### ✅ Implementation
- Fixed dimensions: `200x200px`
- Centered using `position: absolute` or `position: fixed` combined with `transform: translate`

### 🖼️ Screenshot
![TP1 - Centered Box](Docs/screenshots-tp1.png)

---

## 🔝 TP 2: Sticky Top Navigation Menu

### 🎯 Objective
Create a **navigation bar that stays fixed** at the top of the page while scrolling.

### ✅ Implementation
- Horizontal top bar using `position: fixed; top: 0`
- Full width
- Remains visible during scrolling

### 🖼️ Screenshot
![TP2 - Sticky Navigation](Docs/screenshots-tp2.png)

---

## 📑 TP 3: Sticky Table of Contents

### 🎯 Objective
Create a **table of contents (ToC)** that stays visible at the top while reading a long article (with content above it).

### ✅ Implementation
- Long article content added for scrolling
- Table of contents using `position: sticky; top: 0`
- Enhances reading experience during scrolling

### 🖼️ Screenshot
![TP3 - Sticky ToC](Docs/screenshots-tp3.png)

---

## 💬 TP 4: Tooltip on Hover

### 🎯 Objective
Display a **tooltip** when hovering over a button.

### ✅ Implementation
- Interactive button
- Tooltip shown on hover using `position: absolute`
- Positioned above the button with slight offset

### 🖼️ Screenshot
![TP4 - Tooltip](Docs/screenshots-tp4.png)

---

## ⬆️ TP 5: Scroll-to-Top Button

### 🎯 Objective
Create a **scroll-to-top** button positioned at the bottom-right corner of the screen.

### ✅ Implementation
- Fixed button using `position: fixed; bottom: 20px; right: 20px`
- Scrolls smoothly to top when clicked (via JS or `#top` link)
- Visible while scrolling down the page

### 🖼️ Screenshot
![TP5 - Scroll to Top](Docs/screenshots-tp5.png)

---

## 📁 Project Structure

```bash
📂 css-position-practice/
├── tp1-center.html
├── tp2-sticky-menu.html
├── tp3-toc.html
├── tp4-tooltip.html
├── tp5-scroll-top.html
├── style.css
└── screenshots/
    ├── tp1-centered-box.png
    ├── tp2-sticky-nav.png
    ├── tp3-sticky-toc.png
    ├── tp4-tooltip.png
    └── tp5-scroll-top.png



---
🛠️ Technologies Used

    HTML5

    CSS3 (position: relative, absolute, fixed, sticky)

    (Optional) JavaScript for smooth scrolling

✍️ Author

Job MAKOMBELA – Practice project for the Web Design course (HTML/CSS)
Let me know if you'd like:
- The screenshot sections to include actual `<img>` HTML tags instead (for GitHub Pages or preview).
- A French/English bilingual version.
- Help generating the screenshots automatically if you give me your code.

Ready to make it shine! ✨
