# roadmap.lakshay.systems

A growing collection of self-study tools, curated by **signal-to-time ratio** — not completionism.

🔗 **[roadmap.lakshay.systems](https://roadmap.lakshay.systems/)**

---

## Site Structure

```
/                    ← Hub: links to all tools
/roadmap/            ← AI/ML Odyssey (course roadmap + progress tracker)
/ml-prereqs/         ← ML Prerequisites study map
```

---

## Tools

### [AI/ML Odyssey](https://roadmap.lakshay.systems/roadmap/)
A self-study roadmap for AI and machine learning. Track your progress through courses, books, and platforms — all saved locally in your browser.

**Features:**
- **📍 Visual learning path** — Recommended 5-step sequence (Orient → See → Speak → Build → Act)
- **📅 Weekly planner** — Drag courses onto days to plan your study week
- **✅ Progress tracking** — Mark courses as started/completed, check off individual lectures
- **🎨 Light & dark mode** — Toggle between warm cream and rich dark themes
- **🎛️ Tweaks panel** — Customize accent color, density, layout, and planner visibility
- **💾 Local storage** — All progress persists in your browser; no login required

**Courses:** Stanford CS231n, CS224n · CMU 11-785 · MIT 6.S191 · and more  
**Books:** Deep Learning (Goodfellow), D2L, Hands-On ML (Géron)  
**Platforms:** fast.ai, HuggingFace Learn, PyImageSearch

---

### [ML Prerequisites](https://roadmap.lakshay.systems/ml-prereqs/)
An interactive map of the math and programming foundations needed before diving into ML.

**Covers:** Linear Algebra · Calculus · Probability & Statistics · Python · NumPy · and more  
Each topic links to the best free resources available.

---

## Tech Stack

- **React 18** (via CDN) — AI/ML Odyssey
- **Babel Standalone** — inline JSX, no build step
- **Vanilla HTML/CSS/JS** — ML Prerequisites
- **CSS custom properties** — theming
- **localStorage** — progress persistence
- **GitHub Pages** — hosting

---

## Deployment

1. Push to GitHub (`main` branch)
2. **Settings → Pages → Source:** `main` branch, `/root` folder
3. Live at `https://roadmap.lakshay.systems/`

CNAME is set to `roadmap.lakshay.systems`.

---

## License

MIT — fork, adapt, share freely.
