#  Blue Well Game — Official atmospheric website

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> **Descend into the mystery.** A fully responsive, interactive landing page for the fictional puzzle-adventure game *Blue Well* — built with pure HTML, CSS, and vanilla JS.


---

##  About the project

This repository contains a modern, atmospheric one‑page website designed to promote **Blue Well**, an imaginary indie game about ancient wells, forgotten wishes, and psychological puzzles.

The page features:
- Mysterious cosmic / well‑inspired visual identity.
- Smooth animations, floating elements, and interactive UI.
- Fully responsive layout (works on desktop, tablet & mobile).
- Easter eggs and click‑triggered secrets that reflect the game's mysterious tone.

> **Note:** This is a front‑only demo (HTML/CSS/JS) – no backend or game engine included. Perfect for portfolios, game jams, or as a template for indie game landing pages.

---

##  Key features

- **Hero section** – Bold typography, animated well artifact, call‑to‑action buttons.
- **Feature grid** – Highlights core gameplay pillars (riddles, atmosphere, lore, multiple endings).
- **Story & lore panel** – Interactive hover effects and a parallax‑inspired motion on the symbol.
- **Gallery mockup** – Visual cards representing in‑game locations.
- **Newsletter signup** – Front‑end email validation with dynamic feedback.
- **Secret interactions**:
  - Click the *“Discover the secret”* button → reveals a cryptic message.
  - Click on the floating well artifact → water ripple + whispered hint.
  - Navigation links (The Well, Story, etc.) show “coming soon” notifications.
- **Modern styling** – Glassmorphism, gradients, custom scrollbar, and deep blue color palette.

---

##  Built with

| Technology | Purpose |
|------------|---------|
| **HTML5**  | Semantic structure, meta tags for responsiveness |
| **CSS3**   | Flexbox, Grid, keyframe animations, glass morphism, media queries |
| **JavaScript (vanilla)** | Dynamic toasts, email validation, hover effects, ripple animations, DOM manipulation |
| **Font Awesome 6** | Icons for visual polish |
| **Google Fonts** | 'Inter' (sans‑serif) + 'Space Mono' for quotes |

No frameworks, no build steps – open `index.html` and it runs everywhere.

---

##  File structure

```
blue-well-game-website/
├── index.html          # Complete website (styles + scripts included)
└── README.md           # This file
```

Because all styles and scripts are embedded in a single HTML file, serving or sharing is effortless.

---

##  Getting started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/blue-well-game-website.git
cd blue-well-game-website
```

### 2. Open the website

- **Local:** Double‑click `index.html` or use a live server (`npx live-server`).
- **Production:** Deploy to **GitHub Pages**, Netlify, Vercel, or any static host.

### 3. Customize for your own game

- Replace the placeholder text, gallery icons, and image references.
- Update the email signup behavior (currently front‑end only – add a backend or form service).
- Modify colors, fonts, or sections according to your brand.

---

##  Customization ideas

- **Replace the well icon** – Change the `<i class="fas fa-dungeon"></i>` inside `.well-artifact` to any Font Awesome icon (`fa-water`, `fa-well`, `fa-moon`).
- **Update gallery images** – Replace the icon‑based previews with real screenshots (add `<img>` tags inside `.screenshot-img`).
- **Change the secret message** – Edit the text inside the `revealBtn` click listener.
- **Connect newsletter** – Point the subscribe button to a real email API (Mailchimp, ConvertKit, etc.).

---

##  Responsive breakpoints

| Device      | Optimization                         |
|-------------|--------------------------------------|
| Desktop     | Full layout, large hero text, grid   |
| Tablet      | Reduced padding, flexible cards      |
| Mobile      | Stacked sections, smaller font sizes, menu wraps |

Tested on Chrome, Firefox, Safari, and Edge.

---

##  Easter eggs & interactivity

| Action                         | Result                                                   |
|--------------------------------|----------------------------------------------------------|
| Click **“Discover the secret”** | Floating toast with a lore hint: *“Seek the seventh stone.”* |
| Click the **blue well artifact** | Ripple effect + *“The well stirs…”* message.             |
| Hover over **story symbol**     | Symbol subtly moves with mouse (parallax effect).        |
| Click any **nav link**          | “Coming soon” notification (prevents page reload).       |
| Submit **empty/invalid email**  | Friendly validation error.                               |
| Submit **valid email**          | Success message with personalized greeting.              |

---

##  License

Distributed under the **MIT License**. See `LICENSE` file for more information (you can add one, or simply state: *Feel free to use, modify, and share — attribution appreciated*).

---

##  Acknowledgements

- Font Awesome for the incredible icon set.
- Google Fonts for the typography.
- The indie game community for endless inspiration about mysterious wells and forgotten lore.

---

##  Contact

Om Gedam

GitHub: [https://github.com/itsomg134](https://github.com/itsomg134)

Email: [omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)

Twitter (X): [https://twitter.com/omgedam](https://twitter.com/omgedam)

LinkedIn: [https://linkedin.com/in/omgedam](https://linkedin.com/in/omgedam)

Portfolio: [https://ogworks.lovable.app](https://ogworks.lovable.app)
