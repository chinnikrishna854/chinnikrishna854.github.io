# 🚀 Chinni Krishna Bhukya — Portfolio

A space-themed, single-file interactive portfolio for **Chinni Krishna Bhukya**, CS graduate student at San José State University. Built with vanilla HTML, CSS, and Canvas — no frameworks, no dependencies beyond one Google Font.

---

## ✨ Features

### Three-Page Journey
| Page | Description |
|------|-------------|
| **Mission Control** | Landing screen with animated star field, twinkling constellations, and a terminal-style info panel |
| **Solar System** | Fully animated heliocentric solar system — all 8 planets orbit the sun as it drifts across the screen |
| **Portfolio** | Full-content page: About, Education, Experience timeline, Projects, Publications, Patent, Skills, Certifications, Contact |

### Visual & Interactive
- **Animated star fields** with twinkling, constellation lines, and shooting stars on Pages 1 & 2
- **Solar system** rendered on Canvas — planets orbit with correct relative speeds, axial tilt, and ring geometry for Saturn
- **Asteroid belt** drawn between Mars and Jupiter
- **Warp transition** (streaking star lines) when navigating from the solar system to the portfolio
- **Comets** drifting across Pages 1 & 2
- **Planet hover tooltips** — hover any planet to see its name and orbital speed
- **Planet click panels** — click any planet for a detailed info card (diameter, moons, distance, fun fact)
- **Cursor trail** effect on the portfolio page
- **Animated timeline** with scroll-triggered node reveals for the Experience section
- **Scanline CRT flicker** on the app container
- **Web Audio API** — subtle ambient drone on the solar system page, UI click sounds, warp sound effect

---

## 🛠 Tech Stack

- **Vanilla HTML/CSS/JS** — zero build tools, zero npm
- **Canvas API** — star fields, solar system, warp transition, comets, shooting stars
- **Web Audio API** — procedural ambient sound and UI feedback tones
- **Google Fonts** — `Share Tech Mono` for the monospace terminal aesthetic

---

## 📁 File Structure

```
index.html          # Entire site — self-contained single file
README.md           # This file
```

---

## 🚀 Running Locally

Just open `index.html` in any modern browser — no server required.

```bash
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or serve it with any static server:

```bash
npx serve .
python3 -m http.server 8080
```

---

## 🎮 Navigation

| Action | Result |
|--------|--------|
| Click **[ ENTER THE SOLAR SYSTEM ]** | Flies to the solar system page |
| **Click anywhere** on the solar system (not a planet) | Triggers warp transition to portfolio |
| **Hover** a planet | Shows tooltip with name and orbital speed |
| **Click** a planet | Opens detailed info panel |
| Click **✕** on the panel | Closes it |

---

## 📄 Portfolio Sections

1. **About** — Bio, portrait, quick stats
2. **Education** — SJSU M.S. + VIT-AP B.Tech
3. **Experience** — Animated alternating timeline (VIT-AP → MMRFIC internship → SJSU M.S. → Research Assistantship)
4. **Projects** — Featured radar detection system + 3 additional projects
5. **Publications** — 3 IEEE conference papers + 2 journal papers
6. **Patent** — Granted patent: Attendance Monitoring System
7. **Skills** — AI/ML · DevOps & Cloud · Languages & Tools
8. **Certifications** — AWS Certified Cloud Practitioner, IEEE Member · Resume download link
9. **Contact** — Email, phone, LinkedIn, portfolio URL

---

## 🎨 Design System

| Property | Value |
|----------|-------|
| Font | `Share Tech Mono` |
| Background | `#02040f` (deep space) |
| Accent green | `#4dffb4` |
| Accent amber | `#ffb347` |
| All layout | CSS Grid + Flexbox |
| Animations | `requestAnimationFrame` loops |

---

## 🔊 Audio Notes

Sound uses the **Web Audio API** and is triggered by user interaction (browser autoplay policy compliant). Audio includes:

- **Launch beep** — rising tone sequence on the Enter button
- **Ambient drone** — layered sine oscillators + reverb tail on the solar system page
- **Warp sound** — frequency sweep on page transition
- **UI tones** — subtle hover/click feedback on portfolio cards and nav links

---

## 📱 Responsive

The portfolio section adapts to mobile via CSS media queries at `600px`:

- Single-column About grid
- Single-column project grid
- Single-column skills grid
- Single-column contact grid
- Compact nav links

---

## 📬 Contact

**Chinni Krishna Bhukya**  
M.S. Computer Science — San José State University  
San Jose, CA · Open to AI/ML Internships

- Email: chinnikrishna.bhukya@sjsu.edu  
- Phone: 669-312-4465  
- LinkedIn: [linkedin.com/in/chinnikrishna-](https://linkedin.com/in/chinnikrishna-)  
- Portfolio: [chinnikrishna854.github.io](https://chinnikrishna854.github.io)
