# shiatsu_review

Website review and redesign for **Shiatsu Thomas Kolczewski**, Maximilianstraße 15a, 48147 Münster.
Current live site: <https://www.shiatsu-kolczewski.de>

**Shareable page:** <https://eric-musoso.github.io/shiatsu_review/>

| Link | What it is |
| --- | --- |
| [Overview](https://eric-musoso.github.io/shiatsu_review/) | One page with everything: the new website, the review and the film |
| [New website](https://eric-musoso.github.io/shiatsu_review/website/) | The redesigned website, in German, ready to use |
| [Review and plan](https://eric-musoso.github.io/shiatsu_review/review/) | Website and competitor review with a plan to reach four clients a day |
| [REVIEW.md](REVIEW.md) | The same review as plain Markdown |

## What's in the repository

| Path | What it is |
| --- | --- |
| `index.html` | Overview page that links everything together |
| `review/index.html` | The review as a web page |
| `REVIEW.md` | The review as Markdown |
| `website/index.html` | The new website: content, styles and a small script for the phone menu and the film |
| `website/img/` | The practice's own photos and the logo (taken from shiatsu-kolczewski.de) |
| `website/media/shiatsu-film.mp4` | 21-second film (1280×720, no sound) |
| `assets/` | Styles and preview images for the overview and review pages |

## The new website

A single static page: white background, frosted-glass cards, the practice's own photos and logo, and the film. Sections in order:

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

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Use the website on the real domain

Everything is plain HTML with no build step. To replace the current site, upload the contents of `website/` (`index.html`, `img/`, `media/`) to the web root of shiatsu-kolczewski.de.

## Things to keep up to date

- Opening hours, prices and the number of Google reviews are written directly in `website/index.html`.
- The booking buttons link to the existing calendar at `https://www.shiatsu-kolczewski.de/termin/`.
- Review quotes show shortened names; ask the reviewers before showing full names.
- Update the Google Business Profile hours to match the website (Mon 14–19, Tue 14–20, Wed 11–20, Thu 11–19, Fri 17–20).
