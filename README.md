# Code, Coffee & Chaos 🚀
### The Life of a Developer — A Humorous Interactive Journey

A fun, scrollable website that tells the story of a developer's life — learning to code, fighting bugs, surviving late-night deadlines, and finally shipping an app. Click, drag, and interact as the story unfolds. Built with HTML, CSS, and JavaScript.

---

## 📖 Story Structure

| Chapter | Section | Theme |
|---------|---------|-------|
| 00 | **Hero / Overture** | The hook — what this story is about |
| 01 | **Origin** | The First Hello World — learning HTML, CSS, JS |
| 02 | **The Bug** | The debugging crisis — TypeErrors at 11 PM |
| 03 | **Deadline** | It's due tomorrow — the 3 AM grind |
| 04 | **Insight** | The Eureka moment — when it all clicks |
| 05 | **Ship It** | You deployed — confetti, pride, relief |
| 06 | **Epilogue** | The story never ends — new project tomorrow |

---

## ✅ Functional Highlights

### 1. Story Structure (5+ sections)
7 cohesive narrative sections: Hero → Introduction → Exploration → Deadline → Insight → Conclusion → Epilogue

### 2. Scroll-Based Interactions (2+ effects)
- **Parallax grid** — hero background drifts at different scroll speed
- **Scroll-triggered reveals** — every element animates in on scroll (IntersectionObserver)
- **Scroll progress bar** — gradient bar at top tracks reading progress

### 3. Interactive Elements (3+ interactions)
- **Drag & Drop** — skill chips into your personal stack
- **Clickable bug cards** — resolve bugs with audio feedback
- **Accordion** — 5 Stages of Debugging Grief (click to expand/collapse)
- **Coffee cups + progress bars** — click to refuel, bars animate live
- **Hover flip-cards** — insight cards flip to reveal developer wisdom

### 4. Animations (3+ distinct)
- **Cinematic loader** — word-by-word title reveal + terminal lines + fill bar
- **Floating ambient code** — drifting code snippets in the hero background
- **Custom cursor** — smooth ring-follow with state changes
- **Scroll reveal** — fade + translate on every content block
- **Animated counters** — stat numbers count up on scroll
- **Confetti burst** — on deploy success and celebrate button

### 5. Responsive Design
- Fully responsive: Desktop → Tablet → Mobile
- 3-column grids collapse to 2, then 1 column
- Nav adapts; all interactions work on touch devices

---

## 🎮 Interactions Guide

| Interaction | How to use |
|-------------|-----------|
| Drag skills | Drag HTML/CSS/JS/etc chips into the drop zone |
| Fix bugs | Click the red error terminal button to apply fix |
| Debug cards | Click each card to resolve the bug |
| Stages | Click each "Stage of Grief" to expand the story |
| Coffee | Click ☕ cups to refuel and watch progress bars animate |
| Deploy | Hit the "Deploy to Production" button for the full sequence |
| Celebrate | Click "Celebrate the Ship" in the epilogue for confetti |
| Theme | 🌙 button bottom-right toggles dark/light mode |
| Keyboard | ↑ ↓ arrow keys navigate between chapters |
| Easter egg | Hover bottom-right corner... |

---

## 🛠 Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, animations, transitions
- **Vanilla JavaScript** — IntersectionObserver, Web Audio API, Canvas API
- **Google Fonts** — Playfair Display, Outfit, JetBrains Mono
- **Zero dependencies** — no frameworks, no build tools, no npm

---

## 📁 Project Structure

```
dev-story-project/
├── index.html          # Complete self-contained application
├── README.md           # This file
└── assets/
    └── screenshots/    # (Add your own screenshots here)
```

---

## 🎨 Design System

| Token | Value | Usage |
|-------|-------|-------|
| `--green` | `#1ef080` | Primary accent, success states |
| `--cyan` | `#1ecff0` | Secondary accent, code |
| `--orange` | `#ff7a40` | Deadline, warnings |
| `--red` | `#ff3a5c` | Errors, bugs |
| `--purple` | `#a87aff` | Insight, wisdom |
| `--mono` | JetBrains Mono | Code, labels, nav |
| `--serif` | Playfair Display | Headings, story text |
| `--sans` | Outfit | Body copy |

---

## 📝 License

MIT — free to use, modify, and deploy.

---

*Built with caffeine, console.log, and an unreasonable number of browser tabs.*

