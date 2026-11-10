# CRUD — Continue Reading to Update and Develop

**A curated learning atlas for developers.** 5 categories, 20 focused topics, 60 free resources.
Every topic gives you exactly three things: one guide to read, one video to watch, one place to practise.

**[Live site →](https://crud-learning-platform.vercel.app)**

---

## Preview

| Light | Dark |
|:---:|:---:|
| ![Light theme](assets/preview-light.jpg) | ![Dark theme](assets/preview-dark.jpg) |

The site opens in **light** mode on a first visit. Your theme choice is remembered after that.

---

## What makes it different

Every other "learn to code" list hands you 50 links and disappears. CRUD hands you three — and tells you what each one is for.

- **Read** the official or best-known written guide
- **Watch** the single best free video course
- **Practise** with an interactive exercise, playground, or project

That is the whole promise. No sign-up, no paywall, no tracking, no account.

---

## Contents

| # | Category | Topics | Resources |
|:-:|---|:-:|:-:|
| 01 | Programming Languages | 8 | 24 |
| 02 | Resume & Career | 4 | 12 |
| 03 | Companies & Careers | 4 | 12 |
| 04 | Emerging Tech | 4 | 12 |
| 05 | Facts & Insights | 6 quick facts | — |
| | **Total** | **20** | **60** |

---

## Features

- **Light + dark themes** — saved per visitor, starts light
- **Category cards** that tilt and glow toward the cursor on desktop, and respond to press with a finger-following spotlight on touch
- **Instant search** across topics, providers and resources
- **Hash routing** — shareable links to any category, topic or search: `#/c/programming`, `#/t/python`, `#/search?q=sql`
- **Responsive** from 360 px phones to wide desktops
- **Keyboard accessible** with skip link, focus rings and ARIA labels
- **Count-up stats, scroll reveals and step animations** that respect `prefers-reduced-motion`
- **Zero tracking, zero cookies, zero backend**

---

## Tech

Plain **HTML, CSS and vanilla JavaScript** in one self-contained `index.html`.
No framework, no build step, no npm, no dependencies — except Google Fonts.

---

## Project structure

```text
site/
├─ index.html      the entire website (markup, styles, logic, content)
├─ assets/         README preview screenshots
├─ vercel.json     clean URLs + security headers
├─ robots.txt      allow search engines
└─ README.md
```

---

## Run locally

```powershell
# option 1 — just open the file
start index.html

# option 2 — serve it (recommended)
python -m http.server 5173
# then visit http://localhost:5173
```

---

## Deploy

This repo is ready for **Vercel** with no configuration:

1. Push the repo to GitHub.
2. In Vercel, **Add New → Project** and import the repo.
3. Framework preset **Other**, leave build and output commands empty.
4. **Deploy**.

Every push to `main` redeploys automatically.

---

## Editing the site

The master copy lives one level up at `../crud_website.html`. After editing it, sync the deploy copy:

```powershell
Copy-Item ..\crud_website.html .\index.html -Force
```

Then commit and push.

---

## Licence

Personal learning project. Resource links belong to their respective owners.
