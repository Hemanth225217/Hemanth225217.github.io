# Hemanth S — Developer Portfolio

Live site: https://hemanth225217.github.io

A dark, engineering-focused portfolio built with plain HTML, CSS and JavaScript — no framework or build step required, so it deploys directly on GitHub Pages.

## Stack

- **HTML5** — semantic structure, accessible landmarks
- **CSS3** — custom properties, CSS Grid/Flexbox, responsive layout, `prefers-reduced-motion` support
- **Vanilla JavaScript** — `IntersectionObserver` scroll-reveal and scroll-spy nav, canvas grid animation, project filtering, no dependencies

## Structure

```
Hemanth225217.github.io/
├── index.html          # Page structure: hero, about, skills, projects, experience, GitHub, contact
├── style.css            # Theme, layout, animations, responsive rules
├── script.js             # Nav, scroll-spy, reveal animations, typewriter, project filtering
├── assets/
│   ├── profile.jpg      # (optional) add a headshot and reference it in index.html
│   ├── resume.pdf       # add your resume here — linked from the nav/hero "Resume" buttons
│   └── projects/        # optional per-project screenshots
└── README.md
```

## Running locally

Open `index.html` directly, or use VS Code's **Live Server** extension for live reload:

```
Right-click index.html → Open with Live Server
```

## Deployment

Published via **GitHub Pages** from the `main` branch, root folder. Any push to `main` redeploys automatically.

## To finish setup

- [ ] Add `assets/resume.pdf`
- [ ] (Optional) add `assets/profile.jpg` and reference it in the hero section
- [ ] Verify the four project GitHub links in `index.html` point at your actual repo names
- [ ] Fill in the real internship dates/responsibilities in the Experience section
- [ ] Update the LinkedIn URL in the Contact section
