# Productivity Hue Timer

A Pomodoro-style focus timer that shifts the entire background color based on how long you have been working uninterrupted. Built as a single, zero-dependency HTML file.

---

## Links

- **Live Demo:** https://69bbfd95a122f1349ee9f252--ubiquitous-dasik-258bd3.netlify.app
- **Repository:** https://github.com/soaahammmm/Pomodoro-Timer

---

## Concept

Most timers just count down. This one responds to you. The longer you stay focused, the warmer and more energized the color becomes. Pause it and the whole screen desaturates, a subtle but powerful visual cue that your focus streak has broken.

---

## Color Phases

| Phase | Time Range | Color | Meaning |
|-------|------------|-------|---------|
| Warming Up | 0 - 10 min | Blue | Calm, just getting started |
| Deep Focus | 10 - 25 min | Teal | Settled in, building momentum |
| Peak Flow | 25 - 45 min | Purple | Full concentration |
| Burnout Warning | 45+ min | Red | Time to take a break |

---

## Features

- Smooth background color transitions between all focus phases
- Glassmorphism card with animated ambient background orbs
- Pausing desaturates the entire screen to signal a break
- Pulsing red glow at the burnout stage as a visual alert
- Progress bar that fills across the 45-minute window
- Phase indicator pips that activate as you move through stages
- Accurate timing using Date.now() delta tracking, resistant to tab throttling
- Fully responsive layout for desktop, tablet, or snapped windows
- No frameworks, no build step, no dependencies

---

## How to Use

Open index.html directly in any browser. No install or server needed.

To run locally:
1. Download or clone the repository
2. Open index.html in your browser
3. Click Start and focus

---

## Tech Stack

- HTML, CSS, JavaScript (vanilla)
- Google Fonts: DM Mono and Syne
- CSS glassmorphism with backdrop-filter blur
- SVG noise texture overlay
- No external libraries or frameworks

---

## File Structure
productivity-hue-timer
index.html    -- entire app in one file
README.md     -- this file

