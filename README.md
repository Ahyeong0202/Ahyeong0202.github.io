# AhyeongShim.github.io

# Shim Ahyeong — Portfolio Website

> Game Designer · Researcher · System Planner  
> Sungkyunkwan University, Film Television & Multimedia

---

## Overview

Personal portfolio website for **Shim Ahyeong (심아영)**, a game designer and researcher at Sungkyunkwan University. The site presents her work across game design, academic research, and exhibition history — with full bilingual support in English and Korean.

Built as a single-file HTML portfolio with no frameworks or dependencies beyond Google Fonts.

---

## Features

- **Bilingual (EN / KO)** — Full toggle between English and Korean across all sections, including nav, hero, project descriptions, timeline, and contact
- **Scroll-triggered animations** — Section reveals and skill bar fills animate on viewport entry via `IntersectionObserver`
- **Responsive layout** — Two-column grids gracefully collapse to single-column on mobile
- **Custom typography** — `Playfair Display` (display serif) + `Instrument Sans` (body) + `JetBrains Mono` (labels/code)
- **Editorial aesthetic** — Off-white cream base, ink black type, accent red/gold/blue — no neon, no gradients

---

## Sections

| # | Section | Content |
|---|---------|---------|
| — | Hero | Name, role, key awards, stats |
| 01 | About | Bio, research overview, quick facts |
| 02 | Selected Work | 5 projects: games, research papers, tools |
| 03 | Research & Experience | Full chronological activity timeline |
| 04 | Skills | Game design, research, development, tools |
| 05 | Contact | Links + contact form |

---

## Projects

### 🎮 Game Projects
- **My Little Bookstore (나의 작은 서점)** — Hexagonal tile-sorting puzzle game + data-driven difficulty tool. Exhibited at G-Star 2025 (Busan) and Daegu Industry-Academia EXPO.
- **Sweet Candy Night** — Clicker + puzzle mobile game with quest and gacha systems. Graduation project exhibited at SKKU Game & Storytelling 2025.

### 📄 Research Papers
- **Foucault's Apparatus of Power & Game Interactivity** — 🏆 Best Paper, ICCC 2026, Taiwan
- **Before Choice: Panopticism & Player Judgment** — Scopus, GET 2026, Spain
- **IP-MDA Framework** — FDG '25, Austria (Article No. 52, pp. 1–5)

---

## Awards & Recognition

| Year | Award |
|------|-------|
| 2025.12 | 🏆 ICCC 2026 Best Paper Award — Taiwan |
| 2026.07 | Scopus-indexed paper — GET 2026, Spain |
| 2025.05 | FDG '25 Publication — Austria |
| 2024.11 | NYU Capstone Design Exchange — Selected Student |

---

## Tech Stack

```
HTML5 / CSS3 / Vanilla JavaScript
Fonts: Playfair Display · Instrument Sans · JetBrains Mono (Google Fonts)
No build tools. No frameworks. One file.
```

---

## File Structure

```
portfolio/
├── index.html       # Everything lives here
└── README.md        # This file
```

To add project images or documents, place them in the same folder and reference them with relative paths inside the relevant `.project-link-col` element:

```html
<!-- Link to a PDF -->
<a href="paper.pdf" target="_blank" class="proj-link">View Paper →</a>

<!-- Show a thumbnail image -->
<img src="screenshot.png" alt="Project screenshot" style="width:100%;margin-top:1rem;">
```

---

## Customization

**To update content** — All text is inline in `index.html`. Each bilingual string uses `data-en` / `data-ko` span pairs:

```html
<span data-en>English text here</span>
<span data-ko>한국어 텍스트</span>
```

**To add a project** — Copy a `.project-item` block in the `#projects` section and fill in the fields.

**To add a timeline entry** — Copy a `.tl-item` block in the `#activities` section. Available type classes: `tp-award` · `tp-conf` · `tp-exhibit` · `tp-research` · `tp-edu` · `tp-vol`

---

## Contact

- **Email** shimay1031@skku.edu  
- **GitHub** [Ahyeong0202](https://github.com/Ahyeong0202)  
- **University** Sungkyunkwan University — Film, Television & Multimedia

---

*Designed & Built · 2026*
