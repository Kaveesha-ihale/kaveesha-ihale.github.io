# Kaveesha Academic Portfolio Website

This repository contains a Hugo Blox academic portfolio website tailored for a chemistry PhD student and configured for **GitHub Pages deployment**.

## What is included

- A polished home page with a strong chemistry research narrative
- An updated researcher profile
- Experience, skills, and contact sections
- Research project pages
- Publication/research-summary placeholders
- GitHub Pages deployment workflow

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Make sure the repository is named `kaveesha-ihale.github.io` if you want it to publish at the root user site.
3. In GitHub, open **Settings → Pages** and ensure **GitHub Actions** is enabled as the deployment source.
4. Push to the `main` branch. The workflow in `.github/workflows/publish.yml` will build and deploy the site.

## Local development

Install Hugo extended and run:

```bash
hugo server
```

Then open the local address shown in the terminal.

## Main files to customize later

- `content/authors/admin/_index.md` → your bio, education, work, skills, links
- `content/_index.md` → homepage sections
- `content/project/*` → project pages
- `content/publication/*` → publications or research summaries
- `static/uploads/resume.pdf` → replace with your actual CV

## Final cleanup suggestions

Before publishing publicly, replace placeholders such as:

- Undergraduate institution
- Awards and recognitions
- Google Scholar and ORCID links
- Resume PDF
- Any project text you want to make more specific
