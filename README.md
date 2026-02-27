
# 🖼️ Tailwind CSS Grid Image Layout

This project demonstrates a responsive image grid layout built using **Tailwind CSS**. The layout uses CSS Grid utilities to create a multi-column gallery with some images spanning multiple rows and columns.

## 🚀 Features

* Built with **Tailwind CSS (CDN version)**
* 4-column grid layout
* Custom column and row spans
* Square aspect ratio images
* Responsive container styling
* Clean and minimal design

## 📂 Project Structure

```
index.html
README.md
```
[live](https://amrithaamzz.github.io/Grid-Image-Layout/)
![image](./image.png)


## 🛠️ Technologies Used

* HTML5
* Tailwind CSS (via CDN)

```html
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```

## 📸 Layout Details

* `grid grid-cols-4` → Creates a 4-column grid
* `gap-2` → Adds spacing between grid items
* `col-span-2 row-span-2` → Makes selected images span 2 columns and 2 rows
* `aspect-square` → Keeps images perfectly square
* `w-full h-full` → Ensures images fill their grid cell

## ⚠️ Fixes Needed in Current Code

There are two small issues in the HTML:

1. ❌ Extra `'` in container class:

```html
<div class="'container bg-gray-700 ...">
```

✅ Should be:

```html
<div class="container bg-gray-700 ...">
```

2. ❌ Broken `src` attribute in the second image (missing closing quote before `alt`)

Make sure all `src` attributes are properly closed.

## 📷 Preview Concept

* Pink background page
* Centered gray container
* 4-column image grid
* Some large feature images (2x2 span)

## 📦 How to Run

1. Copy the HTML code into `index.html`
2. Open the file in your browser
3. No installation required (Tailwind loaded via CDN)

## 📚 Learning Goals

This project helps you understand:

* Tailwind Grid utilities
* Column and row spanning
* Aspect ratio control
* Basic layout composition


