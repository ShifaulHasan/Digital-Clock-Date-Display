# 🕒 Digital Clock + Date Display

A simple and stylish **live digital clock** web page built with **HTML, CSS, and JavaScript**. It shows the current time (hours, minutes, seconds with AM/PM) and today's date, updating automatically every second.

---

## 🌟 Features

- Live digital clock that updates every second
- 12-hour format with AM/PM
- Current date display: *Weekday, Day Month Year*
- Responsive, modern UI with a gradient background
- Easy to customize with CSS

---

## 🛠️ Technologies Used

| Technology | Usage                                           |
|------------|-------------------------------------------------|
| HTML5      | Page structure                                  |
| CSS3       | Flexbox, gradients, shadows                     |
| JavaScript | DOM manipulation, `setInterval()`, `Date` object |

---

## 📁 Project Structure

```
Digital-Clock-Date-Display/
├── index.html    # Main page
├── style.css     # Styling
├── script.js     # Clock and date logic
└── README.md
```

---

## 🚀 How to Run

1. Clone or download the repository
   ```bash
   git clone https://github.com/ShifaulHasan/Digital-Clock-Date-Display.git
   ```
2. Open `index.html` in any modern web browser
3. The clock and date start updating automatically

---

## 💡 How It Works

1. The JavaScript **`Date` object** provides the current time and date
2. **`setInterval()`** refreshes the display every 1000 ms (1 second)
3. The `#time` and `#date` elements are updated with `textContent`
4. Hours, minutes, and seconds are formatted with leading zeros and AM/PM

---

## ✅ Learning Outcomes

- Understanding the `Date` object and its methods
- Updating HTML dynamically with the DOM
- Using `setInterval()` for repeated execution
- Building a basic responsive UI with CSS

---


---

## ⚡ Next Enhancements

- [ ] Dark / Light mode toggle
- [ ] 24-hour clock option
- [ ] Customizable font and colors
- [ ] Alarm functionality

---

## 👨‍💻 Author

**Md. Shifaul Hasan**
GitHub: [@ShifaulHasan](https://github.com/ShifaulHasan)
