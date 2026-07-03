# Dental Health — Quality Healthcare

A premium, modern single-page website for a dental clinic. Built as a fast, responsive SaaS-style landing experience with smooth animations and a cohesive visual design.

## About
<img width="971" height="829" alt="image" src="https://github.com/user-attachments/assets/76b54eeb-8ed5-4243-b050-175979862166" />

This project showcases professional dental services for **Dental Health**, a clinic focused on quality healthcare in West New York. The site highlights core offerings such as cosmetic dentistry, smile makeovers, veneers, crowns, whitening, implants, and restoration services.

An AI assistant for guided consultations and appointment booking is planned as a future integration.

## Features

- **Animated splash screen** — Count-up intro (0–100) with fade-out transition
- **Fixed navbar** — Desktop menu and animated mobile slide-out navigation
- **Three full-screen sections**
  - **Hero** — Feature bars and main “Dental Care” headline with masked background cards
  - **Smile Gallery** — Cosmetic work showcase, CTA, and interactive service cards
  - **Implant Dentistry** — Restoration services, consultation block, and patient imagery
- **Masked card mosaic** — Sections 1 and 2 share one background image across multiple cards for a seamless layout
- **Staggered scroll reveals** — Elements animate in as sections enter the viewport
- **Fully responsive** — Mobile-first layout with a single `md` (768px) breakpoint

## Tech Stack

| Layer | Technology |
|-------|------------|
| Framework | React 19 |
| Build tool | Vite 8 |
| Language | TypeScript |
| Styling | Tailwind CSS 3 |
| Font | Open Sauce One |

No external UI or icon libraries — the entire landing page lives in a single `App.tsx` file.

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Install dependencies

```bash
npm install
```

### Run development server

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

## Project Structure

```
DENTAL-CLINIC/
├── index.html          # Entry HTML, fonts, page title
├── src/
│   ├── App.tsx         # Full landing page (components, hooks, sections)
│   ├── index.css       # Tailwind + global styles
│   └── main.tsx        # React entry point
├── tailwind.config.js
├── postcss.config.js
└── vite.config.ts
```

## Design

- **Palette:** Black, white, and translucent glass effects (`backdrop-blur`)
- **Typography:** Bold headings with `clamp()` for fluid sizing
- **Interactions:** Hover scale on CTAs, smooth cubic-bezier transitions
- **Imagery:** Remote WebP assets via optimized CDN URLs

## Roadmap

- [ ] AI assistant / chat widget for patient guidance
- [ ] Appointment booking flow
- [ ] Backend integration for scheduling and inquiries

## License

Private project.
