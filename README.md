# ⏰ Digital Clock

A sleek and minimal **Digital Clock** built using HTML, CSS, and JavaScript.  
Displays the **current time in hours, minutes, and seconds** — updated in real-time every second.

## 🌐 Live Demo

> [🔗 Try it here](https://aym3ngharbi.github.io/Digital-Clock/)  
---

## 🚀 Features

- ✅ Real-time updating digital clock
- 🕐 Displays hours, minutes, and seconds
- 🎨 Elegant gradient background
- 💡 Blurred-glass clock card (glassmorphism)
- 🏷️ Time units labeled under each number (Hours, MINS, SEC)

---

## 📁 Project Structure

```plaintext
├── index.html        # Main HTML file
├── style.css         # Styling file (CSS)
└── README.md         # Project documentation
```

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

---

## 🧠 How It Works

1. When the page loads, the script:
   - Fetches the current time using JavaScript's `Date` object.
   - Updates the DOM every second using `setInterval`.
2. The values are padded to always show two digits.
3. Labels like “Hours”, “MINS”, and “SEC” appear under each span using the `::after` pseudo-element.

---

## 📌 Notes

- The clock updates every 1000 milliseconds (1 second).
- `padStart()` ensures leading zeros are displayed correctly (e.g., 08 instead of 8).
- Responsive layout and centered positioning using `transform: translate(-50%, -50%)`.

---

## ✨ Author

**Aymen Gharbi**  
🔗 [Portfolio](https://aym3ngharbi.github.io/Portfolio/) | 💼 [LinkedIn](https://www.linkedin.com/in/gharbi-aymen/) | 🐱 [GitHub](https://github.com/Aym3nGharbi)

---