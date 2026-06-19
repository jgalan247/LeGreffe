# LeGreffe — Engaging Islanders with the States Assembly

A small collection of self-contained civic-engagement prototypes, built around
the proposal **"What's it to me?"** — bringing the work of the Jersey States
Assembly to the Islanders it reaches least.

`index.html` is the landing page (a 10-minute proposal walkthrough). Everything
is plain HTML/CSS/JS with no build step.

## What's here

| Page | Path |
|------|------|
| Landing / proposal (condensed) | `index.html` |
| Landing / proposal (full version) | `index-full.html` |
| What's it to me? (prototype) | `whats-it-to-me.html` |
| You're the Minister | `games/youre-the-minister.html` |
| Motion Builder | `games/motion-builder.html` |
| Order, Order | `games/order-order.html` |
| Steelman | `games/steelman.html` |
| Pass the Law | `games/pass-the-law.html` |
| Vote Wordlet | `vote-wordlet/` |
| Vote Stars | `vote-stars/vote-kids.html` |
| The Democracy Journey | `democracy-journey.html` |

MyTurn and the Jersey Rent Tracker link out to their hosted versions on
`computing-hub.github.io`. Everything else is published in this collection.

## Viewing locally

Open `index.html` in a browser. For the Vote Wordlet PWA to register its
service worker, serve over HTTP rather than `file://`:

```sh
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Figures

Turnout and participation figures cited on the landing page are sourced inline
(Policy Centre Jersey, Bailiwick Express, Channel Eye) and are provisional
pending official release by Vote.je.
