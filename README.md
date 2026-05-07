# Xiaoen Hu — Personal Portfolio

A personal portfolio website built for the CCIT program at the University of Toronto Mississauga. The site presents Xiaoen's background, design work, and contact information through a cohesive dark-themed, multi-page layout inspired by a galaxy/space aesthetic.

---

## Pages

| File | Title | Typology |
|---|---|---|
| `index.html` | Home | Landing Page |
| `about.html` | About Me | Content Heavy |
| `design.html` | Gallery | Photo Rich |
| `contact.html` | Contact | Form |
| `process.html` | Design Process | Documentation |

---

## File Structure

```
portfolio/
├── index.html
├── about.html
├── design.html
├── contact.html
├── process.html
├── README.md
│
├── img/
│   ├── about-me-image.jpg     ← About card thumbnail (home page)
│   ├── design-image.jpg       ← Gallery card thumbnail (home page)
│   ├── contact-image.jpg      ← Contact card thumbnail (home page)
│   ├── resume-image.jpg       ← Process card thumbnail (home page)
│   ├── design1.png            ← Gallery: Future Landscape
│   ├── design2.png            ← Gallery: Mythical Fantasy
│   ├── design3.png            ← Gallery: Sanity World
│   └── schoolwork2.png        ← Gallery: Self-Help System
│
└── media/
    └── me.mp4                 ← Self-introduction video (About page)
```

---

## Getting Started

No build tools or dependencies required. Everything runs in the browser.

1. Download or clone this repository
2. Place your images in the `img/` folder using the filenames listed above
3. Place your intro video in the `media/` folder as `me.mp4`
4. Open `index.html` in any modern browser

---

## Features

- **Responsive layout** — adapts to desktop, tablet, and mobile with a hamburger menu
- **Fixed navigation** — consistent across all pages with active state highlighting
- **Image previews** — every card and gallery item shows a thumbnail; elegant placeholders appear while images are loading or if a file is missing
- **Video player** — self-introduction video on the About page (autoplay, muted, looped) with a descriptive caption bar
- **Lightbox gallery** — click any image on the Gallery page to open a full-size overlay; close with the ✕ button or press `ESC`
- **Contact form** — client-side validation for email and message fields; shows an inline success message on submit
- **No external dependencies** — all styling and scripting is inline; only Google Fonts is loaded from a CDN

---

## Design System

| Token | Value | Usage |
|---|---|---|
| `--ink` | `#0a0a12` | Page background |
| `--cream` | `#f5f2eb` | Primary text |
| `--gold` | `#c9a84c` | Accents, links, borders |
| `--muted` | `#8a8a9a` | Secondary text, placeholders |
| `--card-bg` | `#12121f` | Card and form backgrounds |
| `--border` | `rgba(201,168,76,0.2)` | Subtle dividers and outlines |

**Typefaces**
- [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) (300, 400, 600) — headings and titles
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) (300, 400, 500) — body text and UI

---

## Adding Your Own Images

All image slots have placeholders, so the site works out of the box before you add files. Once you drop an image into `img/` with the correct filename, the placeholder hides automatically.

For the best results:

- **Card thumbnails** (`about-me-image.jpg`, etc.) — 16:9 ratio, at least 800×450px
- **Gallery images** (`design1.png`, etc.) — any ratio; the lightbox scales them to fit the viewport
- **Video** (`me.mp4`) — H.264 encoded, 16:9, ideally under 20MB for fast loading

---

## Browser Support

Tested in current versions of Chrome, Firefox, Safari, and Edge. Uses `backdrop-filter` for the frosted-glass navbar — this is unsupported in older Firefox without a flag, but degrades gracefully to a solid background.

---

## Credits

- Design and development — Xiaoen Hu
- Design direction — inspired by Professor's Bootstrap labs and [Wonbo Woo's](https://wonbo.xyz) personal website
- Fonts — [Google Fonts](https://fonts.google.com)
- University — [University of Toronto Mississauga, CCIT](https://www.utm.utoronto.ca/)

---

*CCIT Portfolio Project — University of Toronto Mississauga, 2024*
