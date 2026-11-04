# lucascedro.github.io

Public portfolio, live at [lucascedro.github.io](https://lucascedro.github.io/). Static HTML, CSS and JavaScript. No build step.

The page is a terminal (`phantonite@garage`) with the dossier under it: evidence (write-ups), background and toolkit.

## What is here

| Path | What it does |
|------|----------------|
| `index.html` | Page, layout, and `window.PORTFOLIO` (the write-ups and the copy) |
| `css/garage.css` | Garage theme |
| `js/den.js` | Terminal: boot text, commands, command history |
| `js/pet.js` | Bitmite, the tamagotchi on a canvas. The only easter egg |
| `assets/avatar.jpg` | Mark used as the avatar and the favicon |

A write-up is one object in `PORTFOLIO.writeups`. Optional fields: `note` and `glance` (`oracle`, `vector`, `impact`). The page renders them. No backend.

## Terminal

`help`, `whoami`, `status`, `stack`, `writeups`, `contact`, `open`, `cat`, `ls`, `clear`. `tamago` or `bitmite` wakes the pet. `sudo`, `nmap` and the other scanners get a refusal: this node is a CV, not a target.
