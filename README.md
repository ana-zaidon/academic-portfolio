# Personal Academic Portfolio — Zaid Khalid Alfier

**Student ID:** 4120485  
**Course:** CS381 — Web Application Development  
**Institution:** Yanbu Industrial College (YIC)  
**Academic Year:** 2025–2026, Second Semester

---

## Project Overview

A fully responsive, semantic, and accessible personal academic portfolio website built with **HTML5** and **custom CSS3** only. No frameworks, no templates, no JavaScript (except a minimal inline hamburger-menu toggle).

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, about snapshot, interests, quote, learning goals |
| Profile | `profile.html` | Full CV: education, experience, skills, languages |
| Contact | `contact.html` | Contact details and card |

## Technical Features

- **Semantic HTML5** — `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<blockquote>`, `<dl>`, `<figure>`
- **Mobile-first design** — base styles target mobile, `@media (min-width: ...)` scales up
- **CSS Flexbox** — navigation bar, hero layout, stats bar, footer
- **CSS Grid** — about section, interests cards, CV columns, contact layout
- **Accessibility** — ARIA labels, `aria-current`, `role` attributes, `.sr-only` utility, `:focus-visible` outlines, semantic landmarks, `alt` text
- **Responsive typography** — `clamp()` for fluid font sizes
- **No CSS frameworks** — all styles written from scratch in `style.css`

## File Structure

```
portfolio/
├── index.html          # Home page
├── profile.html        # Profile / CV page
├── contact.html        # Contact page
├── style.css           # All custom styles
├── photo_4120485.jpg   # Profile photo (add your own)
└── README.md
```

## Setup

1. Clone the repository
2. Add your profile photo as `photo_4120485.jpg` in the root folder
3. Open `index.html` in any modern browser — no build step required

## Submission

Repository link submitted via Blackboard as required.
