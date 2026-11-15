# IPO World

Static website for IPO World. No build step or dependencies.

## Structure
```
ipo-world/
├── index.html
├── style.css
├── assets/logo.svg
└── README.md
```

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Deploy with GitHub Pages
1. Push this folder to a GitHub repository.
2. Go to Settings → Pages.
3. Choose branch `main` and folder `/ (root)`, then save.

## Customize
- Brand green: `--green` in `style.css`.
- Contact form: replace `hello@example.com` in `index.html`.
