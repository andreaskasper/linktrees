# 🔗 linktrees

> Self-hosted, single-page "link in bio" landing pages for West Coast Swing dance events — each one hand-themed to match the event's own branding.

Every page is a single, self-contained HTML file (inline CSS, no build step, no
tracking, no dependencies) served for free via **GitHub Pages**. Think of it as a
lightweight, fully customizable alternative to Linktree.

---

## ✨ Live pages

| Page | Event | When / Where | Link |
|------|-------|--------------|------|
| 🟡 `d-townswing.html` | **D-Town Swing 2026** | Jun 18–21 · Düsseldorf, Germany | [Open](https://andreaskasper.github.io/linktrees/html/d-townswing.html) |
| 🌊 `baltic.html` | **Baltic Swing 2026** | Jun 11–15 · Gdańsk, Poland | [Open](https://andreaskasper.github.io/linktrees/html/baltic.html) |
| 🌾 `rockthebarn.html` | **Rock the Barn** | — | [Open](https://andreaskasper.github.io/linktrees/html/rockthebarn.html) |

Each page bundles the essentials attendees look for: schedule, competitions
(via [scoring.dance](https://scoring.dance)), location, livestream, socials and
featured artists.

---

## 🎨 What makes them nice

- **One file, zero dependencies** — pure HTML + inline CSS, works offline and loads instantly.
- **Bespoke themes** — every event gets its own palette, typography and mood (grunge-yellow license plate, seaside sunshine, barnyard, …).
- **Mobile-first** — designed for the phone screens people actually scan QR codes with.
- **Tasteful motion** — subtle animations that respect `prefers-reduced-motion`.
- **Accessible** — semantic markup and ARIA labels on icons and logos.

---

## 🚀 Usage

The pages are published straight from this repo through GitHub Pages:

```
https://andreaskasper.github.io/linktrees/html/<name>.html
```

Point a QR code or an Instagram/Facebook bio link at that URL and you're done.

## 🛠️ Add a new page

1. Copy an existing file in [`html/`](html/) as a starting point.
2. Rename it to `your-event.html` and update the content, links and colors.
3. Commit to `main` — GitHub Pages redeploys automatically.
4. Share `https://andreaskasper.github.io/linktrees/html/your-event.html`.

---

## 📁 Structure

```
linktrees/
├── html/
│   ├── baltic.html        # Baltic Swing 2026
│   ├── d-townswing.html   # D-Town Swing 2026
│   └── rockthebarn.html   # Rock the Barn
└── README.md
```

---

Made with ☕ and West Coast Swing by [@andreaskasper](https://github.com/andreaskasper).
