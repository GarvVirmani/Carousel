# 🎠 Carousel

## ✨ Description

The **Carousel** project is a simple image carousel built using **HTML**, **CSS**, and **JavaScript**. It automatically cycles through a set of images every few seconds, providing a smooth and engaging viewing experience. Great for learning DOM manipulation and basic animations! 🚀

## 🌟 Features

- 🌈 Automatically cycles through images every **2 seconds**.
- 🔄 Easy to customize with your own image URLs.

## 💻 Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**

## 🚀 Getting Started

### 📦 Prerequisites

- A web browser (e.g., Chrome, Firefox, Safari)
- Basic knowledge of HTML, CSS, and JavaScript

## 🔧 Usage
 - The carousel will automatically start cycling through the images when you open the page.
 - To customize the images, modify the URLs in the JavaScript code.

### 📖 Code Overview
index.html: The main HTML file containing the structure of the carousel.
style.css: The stylesheet that defines the layout and appearance.
script.js: The JavaScript file that handles the image cycling functionality.

## 🔍 Example Code Snippet
Here’s a brief overview of the JavaScript used to create the carousel:


let imgEl = document.querySelector("img");

let arr = [ /* Array of image URLs */ ];

let i = 0;


let id = setInterval(function () {

  imgEl.setAttribute("src", arr[i]);
  
  i = (i + 1) % arr.length;
  
}, 2000);

## 📷 Video

https://github.com/user-attachments/assets/fb6223d7-7f1b-4433-be5e-38ffd162b401


# 🤝 Contributing
I welcome contributions! If you'd like to help improve this project, please fork the repository and submit a pull request with your changes. 💡

