
# 🕒 Digital Clock (JavaScript)

A simple and live digital clock built using HTML, CSS, and JavaScript. It displays the current system time and updates every second in real-time.

---

## 🔍 Features

- Displays current time in HH:MM:SS format
- Updates every second automatically using `setInterval`
- Lightweight and easy to integrate
- No external libraries needed

---

## 📸 Screenshot

![Digital Clock Screenshot](screenshot.png) <!-- Replace with actual screenshot if available -->

---

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript (Vanilla)

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/digital-clock.git
````

2. Navigate to the project folder:

   ```bash
   cd digital-clock
   ```

3. Open `index.html` in your browser:

   ```bash
   open index.html
   ```

   *(or just double-click the file)*

---

## 📂 File Structure

```
digital-clock/
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 📜 Code Preview

```js
const clock = document.querySelector('#clock');

setInterval(function () {
  let date = new Date();
  clock.innerHTML = date.toLocaleTimeString();
}, 1000);
```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

