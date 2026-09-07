# 🖼️ Image Slider

A simple and responsive **Image Slider** built using **HTML, CSS, and JavaScript**.

This project demonstrates how to create an interactive image , allowing users to navigate between images using navigation buttons and indicators.

## 🚀 Features

* 🖼️ Display images
* ⬅️ Previous image button
* ➡️ Next image button
* 🔘 Navigation indicators
* ✨ Smooth image transitions
* 📱 Responsive design
* 🚫 No external libraries or frameworks

## 🛠️ Technologies Used

* **HTML5** — Structure of the image slider
* **CSS3** — Styling, layout, and transitions
* **JavaScript (ES6+)** — Slider functionality and DOM manipulation

## 📂 Project Structure

```text
Image-Slider/
│
├── index.html
├── style.css
├── script.js
├── imgs
└── README.md
```

## ⚙️ How It Works

The Image Slider contains multiple images that are displayed one at a time.

Users can navigate through the images using the **Previous** and **Next** buttons. The current image is also indicated using navigation dots.

### Slider Flow

```text
User opens the application
          ↓
First image is displayed
          ↓
User clicks Previous / Next
          ↓
JavaScript changes the active image
          ↓
Navigation indicator is updated
```

## ▶️ How to Run

### Using VS Code + Live Server

1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension if you don't already have it.
3. Open `index.html`.
4. Right-click on the file.
5. Select **Open with Live Server**.

The Image Slider will open automatically in your browser.

### Open Directly

You can also open the `index.html` file directly in any modern web browser.

## 💡 JavaScript Concept

The slider uses JavaScript to keep track of the currently active image.

For example:

```javascript
let currentIndex = 0;
```

When the user clicks the **Next** button, the index is increased:

```javascript
currentIndex++;
```

When the **Previous** button is clicked, the index is decreased:

```javascript
currentIndex--;
```

The displayed image and active navigation indicator are then updated based on the current index.

## 📸 Screenshots

<img width="2097" height="857" alt="Screenshot 2026-09-07 072502" src="https://github.com/user-attachments/assets/92bf57e2-7c03-4d84-8263-c4ee7da3a9dd" />



<img width="2072" height="897" alt="Screenshot 2026-09-07 072523" src="https://github.com/user-attachments/assets/8025979f-565f-498d-9d8f-483d72ebe11f" />


## 🔮 Future Improvements

Possible improvements for future versions:

* 🔄 Automatic image sliding
* ⏱️ Customizable slide interval
* ⏸️ Pause slider on hover
* ⌨️ Keyboard navigation
* 🖼️ Fullscreen image mode
* 🎨 Different transition animations

## 👨‍💻 Author

**Omar Ahmed Sallam**

Junior Full-Stack (.Net & Angular) Develoer

* GitHub: [Omar-SallaM0](https://github.com/Omar-SallaM0)

## 📄 License

This project is open source and available for learning and personal use.
