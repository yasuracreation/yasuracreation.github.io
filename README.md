# Yasura Dissanayake — Portfolio

Personal portfolio site for [Yasura Dissanayake](https://www.linkedin.com/in/yasura-dissanayaka/), full-stack software engineer.

- **Live (after deploy):** [yasuracreation.github.io](https://yasuracreation.github.io)
- **Tech:** HTML, CSS, minimal JS — static, no build step.

## Hosting on GitHub Pages

See **[DEPLOY.md](DEPLOY.md)** for step-by-step instructions to host this at **https://yasuracreation.github.io**.

## Local preview

Open `index.html` in a browser, or use a simple server:

```bash
# Python 3
python3 -m http.server 8000

# Then open http://localhost:8000
```

## Structure

- `index.html` — Single-page content (hero, about, skills, projects, contact)
- `styles.css` — Layout and styling

All links use relative paths so the site works at any base URL (root or subpath).
