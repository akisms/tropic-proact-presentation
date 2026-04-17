# Tropic Proact — Product Marketing Take-Home

An interactive presentation for the Tropic PMM take-home exercise, by **Ayman Kotob**.

Live deck: open `index.html` in any browser — no build step.

## What's in here

| File | Purpose |
|------|---------|
| `index.html` | Wrapper with a version-switcher sidebar. Loads the selected version in an iframe. |
| `v1.html` | First draft of the presentation. |
| `v2.html` | Current draft, with feedback incorporated. |
| `server.js` | Tiny Node static server (optional). |
| `ayman-headshot.jpeg` | Cover-slide photo. |

## Running it

**Option 1 — open directly in a browser:**
```
open index.html
```

**Option 2 — serve locally (useful for the iframe to load cleanly):**
```
node server.js
# then visit http://localhost:3000
```

## Controls

Inside the presentation:

| Key | Action |
|-----|--------|
| `P` | Enter / exit presentation mode |
| `← / →` or `Space` | Next / previous slide |
| `Esc` | Exit presentation mode |
| Scroll wheel | Advance slides (in presentation mode) |

In the version-switcher sidebar:

| Key | Action |
|-----|--------|
| `[` / `]` | Cycle previous / next version |
| `\` | Hide / show the sidebar |

Entering presentation mode inside a version auto-hides the sidebar so the deck takes the full screen.

## Stack

Plain HTML, CSS, and vanilla JavaScript. No framework, no build step. Fonts are loaded from Google Fonts (Inter + Instrument Serif).
