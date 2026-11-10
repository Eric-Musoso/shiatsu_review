# Shiatsu Kolczewski – Website

New website for **Shiatsu Thomas Kolczewski**, Maximilianstraße 15a, 48147 Münster.
Current live site: <https://www.shiatsu-kolczewski.de>

A single static page in German: white background, frosted-glass cards, the practice's own photos and logo, and a 21-second film.

## Contents

| Path | What it is |
| --- | --- |
| `index.html` | The whole website: content, styles and a small script for the phone menu and the film |
| `img/` | The practice's own photos and the logo (taken from shiatsu-kolczewski.de) |
| `media/shiatsu-film.mp4` | 21-second film (1280×720, no sound) |

## Sections

1. Start screen with headline, booking button and Google rating
2. Film "Shiatsu in 21 Sekunden"
3. Behandlung – when people come for shiatsu
4. Stimmen – 5,0 from 33 Google reviews, six real review excerpts
5. Ihr erster Besuch – four steps
6. Angebote und Preise – 90 € treatment, 405 € 5-session card, 45 € Shiatsu kompakt, vouchers from 50 €
7. Über mich
8. Die Praxis – photo gallery
9. Termin und Kontakt – address, phone, e-mail, opening hours, Instagram, Facebook, LinkedIn

## View it locally

Open `index.html` in a browser, or run a small local server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publish it

The site is plain HTML with no build step. It can be hosted on any web space, for example:

- **GitHub Pages:** repository Settings → Pages → Branch `main`, folder `/ (root)`.
- **Your current host:** upload `index.html`, `img/` and `media/` to the web root.

## Things to keep up to date

- Opening hours, prices and the number of Google reviews are written directly in `index.html`.
- The booking buttons link to the existing calendar at `https://www.shiatsu-kolczewski.de/termin/`.
- Review quotes show shortened names; ask the reviewers before showing full names.
