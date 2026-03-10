[portfolio-README.md](https://github.com/user-attachments/files/25865148/portfolio-README.md)
# 🚀 Mustapha Bello Muhammad — Developer Portfolio

> Personal portfolio website for **Mustapha Bello Muhammad**, Full Stack Software Engineer.

[![Live Site](https://img.shields.io/badge/Live-Portfolio-yellow?style=flat-square)](https://moustee.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-moustee-black?style=flat-square&logo=github)](https://github.com/moustee)

---

## Overview

A single-page portfolio built with pure HTML, CSS, and JavaScript — no frameworks, no build tools, just clean and fast. Designed to be memorable, with a dark theme, animated cursor, typewriter effect, scroll-reveal animations, and a floating skill ticker.

## Features

- 🎨 **Custom animated cursor** with ring follow effect
- ✍️ **Typewriter tagline** cycling through phrases
- 🌊 **Scroll-reveal animations** on every section
- 🏷️ **Live skill ticker** scrolling across the page
- 📱 **Fully responsive** — works on mobile, tablet, and desktop
- ⚡ **Zero dependencies** — no npm, no build step, just open `index.html`
- 🌐 **GitHub Pages ready** — deploy instantly

## Sections

| Section | Description |
|---|---|
| **Hero** | Name, animated tagline, CTA buttons |
| **About** | Bio and tech skill cards |
| **Projects** | MediTrack, FlowDesk, AgroLink with stack tags |
| **Experience** | Kano Systems & eHealth Africa |
| **Contact** | Email and GitHub links |

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, animations, grid, flexbox
- **Vanilla JavaScript** — Cursor, typewriter, IntersectionObserver
- **Google Fonts** — Syne (display) + DM Sans (body)

## Getting Started

```bash
# Clone the repo
git clone https://github.com/moustee/portfolio.git
cd portfolio

# Open directly in browser — no server needed
open index.html
```

Or simply drag `index.html` into any browser.

## Deployment (GitHub Pages)

```bash
# 1. Create a new repo named: moustee.github.io
# 2. Push the file
git init
git add index.html
git commit -m "Launch portfolio"
git remote add origin https://github.com/moustee/moustee.github.io.git
git push -u origin main

# Your site will be live at:
# https://moustee.github.io
```

## Customization

All content is in `index.html`. Key things to update:

| What | Where in the file |
|---|---|
| Projects | `<!-- Projects -->` section |
| Email link | `href="mailto:..."` in Contact |
| Tagline phrases | `phrases` array in `<script>` |
| Skills | `.skills-grid` cards in About |
| Experience | `.exp-grid` in Experience |

## Projects Featured

| Project | Stack | Repo |
|---|---|---|
| 🏥 MediTrack | Django, Python, MySQL | [github.com/moustee/meditrack](https://github.com/moustee/meditrack) |
| ⚡ FlowDesk | Django REST, PostgreSQL, HTMX | [github.com/moustee/flowdesk](https://github.com/moustee/flowdesk) |
| 🌾 AgroLink | Django, MySQL, Africa's Talking | [github.com/moustee/agrolink](https://github.com/moustee/agrolink) |

## Author

**Mustapha Bello Muhammad**
- GitHub: [@moustee](https://github.com/moustee)
- Role: Full Stack Software Engineer
- Experience: Kano Systems · eHealth Africa

## License

MIT — feel free to use this as inspiration for your own portfolio.
