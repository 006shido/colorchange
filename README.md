# 🎨 Background Color Changer

A simple and interactive web project built using **HTML, CSS, and JavaScript** that changes the webpage background color with a single button click.

## 📌 Features

* Modern and responsive design
* Centered card layout
* Smooth background color transitions
* Hover and click button animations
* Random color generation from a predefined color palette
* Beginner-friendly code structure

## 🚀 Preview

When the user clicks the **"Click Here"** button, the webpage background changes to a random color selected from the color array.

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript

## 📂 Project Structure

```text
Background-Color-Changer/
│
├── index.html
└── README.md
```

## ⚙️ How It Works

1. A list of colors is stored in a JavaScript array.
2. When the button is clicked, the `changeColor()` function runs.
3. A random color is selected using `Math.random()`.
4. The selected color is applied to the webpage background.

### JavaScript Logic

```javascript
const randomColor =
colors[Math.floor(Math.random() * colors.length)];

document.body.style.background = randomColor;
```

## 🌐 Live Demo

Try the project here:

https://006shido.github.io/colorchangehtml/

