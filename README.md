# Nikhil Choudhary — Portfolio

Personal creative portfolio site. A single-page static site built with plain HTML, CSS and JavaScript, no build step required.

## Project structure

```
portfolio/
├── index.html      # Page markup
├── css/
│   └── style.css   # All styles
├── js/
│   └── script.js   # Footer year + scroll-reveal animation
├── assets/         # Images, icons, fonts
├── .gitignore
└── README.md
```

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Works out of the box with GitHub Pages: in the repo settings, set Pages to deploy from the `main` branch root.
