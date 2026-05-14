# TZ Board

Timezone dashboard for office TVs. Built for MSPs to display client/office times at a glance.

**Live:** https://lachlanalston.github.io/tz-board/

---

## How it works

Two modes, one URL:

| Mode | URL |
|------|-----|
| Builder | `https://lachlanalston.github.io/tz-board/` |
| Display | `https://lachlanalston.github.io/tz-board/?d=<config>` |

Config is base64-encoded JSON in the URL — no backend, no login.

---

## Usage

1. Open the builder
2. Add clocks via **Quick Add** chips or the label + timezone form
3. Reorder with ↑↓, remove with ✕
4. Click **Generate Dashboard Link**
5. Copy the link → paste into TV browser

---

## Layouts

Automatically adapts to clock count:

| Clocks | Layout |
|--------|--------|
| 1 | Single centered |
| 2 | Side by side |
| 3 | Row of 3 |
| 4 | 2 × 2 grid |
| 5 | 3 top + 2 bottom (centered) |
| 6 | 3 × 2 grid |
| 7 | 4 top + 3 bottom (centered) |
| 8 | 4 × 2 grid |

---

## Timezones

Presets include: Local, New York, Chicago, Denver, Los Angeles, Las Vegas, London, Amsterdam, Dubai, Mumbai, Singapore, Tokyo, Sydney, Melbourne, Perth, Auckland.

Custom IANA timezones supported via the dropdown (e.g. `America/Phoenix`).

---

## Deploy your own

```bash
git clone https://github.com/lachlanalston/tz-board
cd tz-board
# edit index.html if needed
git push
```

GitHub Pages serves from `master` root — no build step.

---

## Stack

Vanilla HTML/CSS/JS · JetBrains Mono + Inter (Google Fonts) · Single file · No framework · No build
