 Stopwatch Web Application

A clean, responsive stopwatch web app built with pure **HTML**, **CSS**, and **JavaScript** — no frameworks, no dependencies.

> Dark glassmorphic UI with color-coded controls and live lap tracking.

 Features

-  **Start / Pause / Resume** — full timer control
- **Reset** — clears timer and all lap records
-  **Lap Recording** — records split time and cumulative total
-  **Best Lap** highlighted in green
-  **Slowest Lap** highlighted in orange/red
-  **Responsive Design** — works on mobile and desktop
-  **Smooth 60fps** display using `requestAnimationFrame`
-  **Color-coded buttons** — Start (green), Pause (amber), Lap (yellow), Reset (red)


 Getting Started

 Option 1 — Open directly in browser
1. Download or clone this repository
2. Double-click `stopwatch.html`
3. It opens instantly in your browser — no server needed

 Option 2 — VS Code + Live Server
1. Open the project folder in **VS Code**
2. Install the **Live Server** extension (`Ctrl + Shift + X` → search "Live Server")
3. Right-click `stopwatch.html` → **Open with Live Server**
4. Your browser auto-opens and refreshes on every save

 📁 Project Structure


stopwatch-app/
│
├── stopwatch.html      # Main application file (HTML + CSS + JS)
└── README.md           # Project documentation


> All HTML, CSS, and JavaScript are contained in a single file for simplicity.


 Built With

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and layout |
| CSS3 | Styling, animations, glassmorphic design |
| Vanilla JavaScript | Timer logic, lap tracking, DOM updates |
| `requestAnimationFrame` | Smooth 60fps timer rendering |
| Google Fonts | JetBrains Mono + Inter typography |


 How to Use

| Button | Action |

| **Start** | Begins the stopwatch; label changes to "RUNNING" |
| **Pause** | Freezes the timer |
| **Lap** | Records current lap split (only active while running) |
| **Reset** | Stops timer and clears all laps |


 Author

**Shreyas S**

 Internship

Prodigy InfoTech Web Development Internship


