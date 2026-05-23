<h1 align="center">📚 3D Interactive Book Cover</h1>

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status" />
</div>

<br>

## 📖 About The Project

The **3D Interactive Book Cover** is a highly engaging, pure CSS component designed to revolutionize product showcases for digital bookstores, online libraries, and e-commerce platforms. It transforms a flat 2D image into a fully interactive 3D book object. Users can hover over the book to view it from a dynamic angle, and click (active state) to flip it completely and read the back cover, perfectly simulating the physical experience of holding a book.

### 🎨 Visual Demo

[3D Book Online Demo](https://hosein-raz.github.io/book-3d/)

<img src="https://github.com/Hosein-raz/book-3d/blob/main/book-3d.gif" alt="3D Book Online Demo" />

## ✨ Key Technical Features

This project demonstrates advanced knowledge of CSS 3D transforms and interactive states without relying on JavaScript:

* **True 3D Perspective:** Utilizes the `perspective: 1000px` property on the parent container alongside `transform-style: preserve-3d` to establish a realistic 3D spatial environment.
* **Complex CSS Geometry:** Cleverly constructs the physical volume of the book using pseudo-elements:
  * `::before` acts as the book's spine, rotated perpendicularly (`rotateY(90deg)`) with a modified `transform-origin`.
  * `::after` serves as the back cover, utilizing `rotateY(180deg)` and `translateZ(60px)` to sit perfectly behind the front cover.
* **Interactive States:** * Features a smooth `transition: 0.5s` that tilts the book (`rotateY(30deg)`) on `:hover`.
  * Allows users to flip the book completely to view the back cover using the `:active` pseudo-class.
* **Performant Animations:** All interactions are handled via hardware-accelerated CSS transforms.

## 🚀 How to Use

You can easily integrate this 3D component into your own online store or portfolio:

1. Clone the repository:
```bash
git clone https://github.com/Hosein-raz/book-3d.git
```
2. Copy the HTML structure from `index.html`.
3. Replace `images/1.png` (Front Cover) and `images/2.png` (Back Cover) with your own book graphics.
4. Import the styling from `style.css` into your project's stylesheet.

## 📂 Project Structure

```
book-3d/
├── images/       # Contains the front and back cover graphics of the book
├── index.html    # The semantic structure holding the book images
└── style.css     # 3D geometry, perspective, hover, and active logic
```

## 🤝 Let's Connect

<br>

<div align="center">
  <a href="https://www.linkedin.com/in/hosein-razghandi" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://github.com/Hosein-raz" target="_blank">
    <img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="mailto:hoseinrazqandi7@gmail.com">
    <img src="https://img.shields.io/badge/-Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

<br>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Hosein-raz&label=Repository%20Views&color=F97316&style=for-the-badge" alt="Views Counter" />
</div>
