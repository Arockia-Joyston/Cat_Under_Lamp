# 🐱 Cat Under Lamp (Interactive Web Project)

🔗 **Live Demo:** https://arockia-joyston.github.io/Cat_Under_Lamp/

This is a simple and interactive web project where a cat reacts to a lamp being turned ON and OFF.

---

## 🚀 Features

* Toggle light using ON/OFF buttons
* Dynamic image switching using JavaScript
* Clean UI using Tailwind CSS
* Beginner-friendly project for learning DOM manipulation

---

## 🖼️ How It Works

* 💡 **ON Button**

  * Bulb turns ON
  * Cat becomes fully visible

* 🌑 **OFF Button**

  * Bulb turns OFF
  * Only cat eyes are visible

---

## 🛠️ Technologies Used

* HTML5
* Tailwind CSS
* JavaScript (DOM Manipulation)

---

## 📁 Project Structure

```
project-folder/
│
├── index.html
└── assets/
    ├── bulb-go-on-img.webp
    ├── bulb-go-off-img.png
    ├── cat-img.webp
    └── cat-eyes-img.webp
```

---

## ⚙️ How to Run Locally

1. Clone this repository:

   ```
   git clone https://github.com/arockia-joyston/Cat_Under_Lamp.git
   ```
2. Open `index.html` in your browser
3. Click ON/OFF buttons to interact

---

## 📌 Key JavaScript Logic

```javascript
OnBtn.addEventListener("click", ()=>{
    bulb.src = "assets/bulb-go-on-img.webp"
    cat.src = "assets/cat-img.webp"
})

OffBtn.addEventListener("click", ()=>{
    bulb.src = "assets/bulb-go-off-img.png"
    cat.src = "assets/cat-eyes-img.webp"
})
```

---

## 📚 What You Learn

* DOM manipulation using `getElementById`
* Event handling in JavaScript
* Updating UI dynamically
* Basic Tailwind styling

---

## ⭐ Future Improvements

* Add smooth animations
* Add sound effects 🔊
* Make it mobile responsive
* Add dark/light mode toggle

---

## 🙌 Author

**Arockia Joyston**

---

💡 *A great beginner project to start your JavaScript journey!*
