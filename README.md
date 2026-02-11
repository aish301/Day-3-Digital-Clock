# ⏰ Digital Clock Application

![Digital Clock Application](images/Output.png)

A simple and elegant Digital Clock built using **HTML, CSS, and JavaScript**.

This project displays the current time in real-time and updates every second using JavaScript.

## Features

- 🕒 Displays real-time hours, minutes, and seconds
- 🔄 Updates automatically every second
- 🎨 Styled with modern UI (Neon + Glassmorphism effect)
- 📱 Responsive design
- 💡 Clean and beginner-friendly JavaScript logic

## Technologies Used

- HTML5
- CSS3 (Flexbox, Glass Effect, Neon Glow)
- JavaScript (Date object, setInterval, DOM manipulation)

## How It Works

1. JavaScript fetches current time using the `Date()` object.
2. Extracts hours, minutes, and seconds.
3. Formats time to always show two digits.
4. Updates the DOM using `textContent`.
5. Uses `setInterval()` to update every 1000 milliseconds (1 second).
