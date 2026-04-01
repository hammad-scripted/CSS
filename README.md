# 🎨 CSS Complete Guide

A comprehensive guide to **CSS (Cascading Style Sheets)** covering fundamentals to advanced concepts. This repository is designed for learning, revision, and interview preparation.

---

# 📌 What is CSS?

CSS is used to style and layout web pages — for example, to change colors, fonts, spacing, and positioning of elements.

---

# 🧱 CSS Basics

## 🔹 Syntax

```css
selector {
  property: value;
}
```

## 🔹 Example

```css
h1 {
  color: blue;
  font-size: 24px;
}
```

---

# 🎯 Selectors

* Element Selector → `div`
* Class Selector → `.className`
* ID Selector → `#idName`
* Universal Selector → `*`

---

# 📦 Box Model

Every element is a box consisting of:

* Content
* Padding
* Border
* Margin

```css
div {
  margin: 10px;
  padding: 20px;
  border: 2px solid black;
}
```

---

# 📍 Positioning

Controls how elements are placed on the page.

## Types:

* `static` (default)
* `relative`
* `absolute`
* `fixed`
* `sticky`

## Example (Centering)

```css
.parent {
  position: relative;
}

.child {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```

---

# 🎨 Colors & Units

## Colors:

* Named → `red`
* HEX → `#ff0000`
* RGB → `rgb(255,0,0)`
* RGBA → `rgba(255,0,0,0.5)`

## Units:

* px, %, em, rem, vh, vw

---

# 📐 Layout Systems

## 🔹 Flexbox (1D Layout)

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

---

## 🔹 Grid (2D Layout)

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}
```

---

# 🌑 Shadows

## Box Shadow

```css
div {
  box-shadow: 5px 5px 10px rgba(0,0,0,0.3);
}
```

## Text Shadow

```css
h1 {
  text-shadow: 2px 2px 5px gray;
}
```

---

# 🎬 Transitions

Smoothly animate property changes.

```css
button {
  transition: background 0.3s ease;
}

button:hover {
  background: red;
}
```

---

# 🎞️ Animations

## Keyframes

```css
@keyframes move {
  0% { transform: translateX(0); }
  100% { transform: translateX(200px); }
}
```

## Apply Animation

```css
.box {
  animation: move 2s ease infinite;
}
```

---

# 📱 Responsive Design

## Media Queries

```css
@media (max-width: 768px) {
  body {
    background: lightgray;
  }
}
```

---

# ⚡ Best Practices

* Use **Flexbox & Grid** for layouts
* Prefer `rem` over `px` for scalability
* Use `transform` & `opacity` for animations
* Avoid excessive use of `!important`
* Keep CSS modular and reusable

---

# 🧠 Quick Cheat Sheet

```css
display: flex;
display: grid;
position: relative;
box-shadow: 0 0 10px rgba(0,0,0,0.2);
transition: all 0.3s ease;
animation: move 2s infinite;
```

---

# 🚀 Conclusion

CSS is essential for creating visually appealing and responsive web applications. Mastering layout systems, positioning, and animations will help you build modern UI designs efficiently.

---

# ⭐ Contribute

Feel free to fork this repo, improve the notes, and add more examples!

---

# 📌 Author
Mohammad Hammad

Made with ❤️ for learning and development.
