# Print It! – First Steps in JavaScript 🖼️

## 🎯 Project Objectives

The objective of this project was to **discover and practice the fundamentals of JavaScript** by adding interactivity to a static website for a printing company.  
The goal was to make the homepage more dynamic and engaging by implementing an **interactive image carousel** controlled through user actions.

This project is part of the **Web Integrator training course – OpenClassrooms**.

---

## 🧠 Skills Developed

- **JavaScript Fundamentals** – Understanding the basics of variables, functions, loops, arrays, and DOM manipulation.  
- **DOM Interaction** – Selecting, modifying, and updating HTML elements dynamically using JavaScript.  
- **Event Handling** – Implementing `click` event listeners to trigger carousel navigation.  
- **Conditionals and Logic** – Creating logic to handle navigation between images and looping the carousel infinitely.  
- **Dynamic Content Update** – Synchronizing image changes with text captions and bullet indicators.  
- **Integration with HTML & CSS** – Combining JavaScript behavior with existing HTML and CSS structure.  
- **Debugging Techniques** – Using `console.log()` and browser dev tools to test and correct code behavior.  
- **Version Control** – Using Git and GitHub to manage project versions and code history.  

---

## ⚙️ Technical Stack

- **Languages:** HTML5, CSS3, JavaScript (ES6)  
- **Tools:** Visual Studio Code, Git, GitHub  
- **Development Environment:** Local web browser environment (no build tools required)  
- **Version Control:** Git / GitHub  

---

## 🚀 Features Implemented

### 🎠 Interactive Carousel
- Display of multiple slides containing images and text.  
- Left and right navigation arrows added to move between images.  
- Event listeners implemented on both arrows to detect user clicks.  
- Bullets added below the slider to indicate the current active image.  
- Active bullet dynamically updated when slides change.  
- Automatic looping implemented to cycle continuously through images.  

### ⚙️ Carousel Logic
- On **right arrow click** → show the next image, update caption and active bullet.  
- On **left arrow click** → show the previous image, update caption and active bullet.  
- If the user reaches the **last image** and clicks right → return to the **first image**.  
- If the user reaches the **first image** and clicks left → jump to the **last image**.  
- Text updates dynamically to match the displayed image.  

---

## 📦 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, etc.)
- A text editor (recommended: Visual Studio Code)
- Basic understanding of HTML and CSS

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Julie-Des/Projet5-oc
   ```
   
2.  **Open `index.html` in your web browser.** No server setup is required as it's a static website.

### Running Locally

Simply open the `index.html` file in your web browser. The website should load and function as expected. The banner slideshow will be functional, and you can navigate through the different sections of the page.

---

## 📂 Project Structure

```
├── index.html          # Main HTML file
├── assets/
│   ├── style.css       # CSS stylesheet
│   ├── script.js       # JavaScript file for banner functionality
│   └── images/
│       ├── logo.png    # Company logo
│       └── slideshow/  # Images for the banner slideshow
│           ├── slide1.jpg
│           ├── slide2.jpg
│           └── ...
└── README.md         # Project documentation
```
---

## 🌍 Deployment

The project is deployed on GitHub:
https://julie-des.github.io/Projet5-oc/

---

## 📬 Contact

Deshayes Julie - julie.deshayes14@gmail.com

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
