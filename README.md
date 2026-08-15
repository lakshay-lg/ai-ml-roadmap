# roadmap.lakshay.systems

A growing collection of self-study tools, curated by **signal-to-time ratio** — not completionism.

🔗 **[roadmap.lakshay.systems](https://roadmap.lakshay.systems/)**

---

## Site Structure

```
/                    ← Hub: links to all tools
/roadmap/            ← AI/ML Odyssey (course roadmap + progress tracker)
/ml-prereqs/         ← ML Prerequisites study map
/cs-fundamentals/    ← CS Fundamentals study map (systems courses)
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

### [CS Fundamentals](https://roadmap.lakshay.systems/cs-fundamentals/)
A roadmap for building the systems you use every day, from scratch — instead of just using them as black boxes.

**Covers:** MIT 6.1810 (xv6 OS) · Stanford CS144 (build TCP) · CMU 15-445 (BusTub database) · CMU 15-418/Stanford CS149 (parallel & GPU computing) · MIT 6.5840 (MapReduce, Raft, distributed KV stores)  
**Also links:** Berkeley CS186, UW CSE 452, and Brown CS1380 as further reps in the same genre  
Every lab is public, free, and self-gradable — no enrollment required.

---

## Tech Stack

- **React 18** (via CDN) — AI/ML Odyssey
- **Babel Standalone** — inline JSX, no build step
- **Vanilla HTML/CSS/JS** — ML Prerequisites, CS Fundamentals
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
