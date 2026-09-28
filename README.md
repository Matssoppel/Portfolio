# Mats Ugland – Portfolio

Personal portfolio of Mats Ugland, a designer working across product design, UX and interaction design. The site presents selected projects and a CV (in Norwegian).

## Pages

| File | Page |
|---|---|
| `index.html` | Home and project overview |
| `politiet-i-lomma.html` | Politiet i lomma |
| `snakk-til-meg.html` | Snakk til meg |
| `digitalisering-av-byggeplass.html` | Prosjekthub – digitalisering av byggeplass |
| `workshops.html` | Campus workshops |
| `pultlampe.html` | Ampær desk lamp |
| `cv.html` | CV |

## Built with

- Plain HTML and CSS, no framework or build step
- [Poppins](https://fonts.google.com/specimen/Poppins) from Google Fonts
- Designed in Figma

## Project structure

```
.
├── *.html   # one file per page
└── img/     # images, prefixed with the page they belong to
```

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deployment

The site is hosted with GitHub Pages from the `main` branch (root folder). Changes pushed to `main` go live automatically.
