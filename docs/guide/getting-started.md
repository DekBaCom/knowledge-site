# Beginner's Guide

Welcome! This guide helps you build and deploy the site.

## 1) Edit content
All pages are simple **Markdown** files in the `docs/` folder.

## 2) Preview locally
```bash
pip install -r requirements.txt
mkdocs serve
```

## 3) Deploy automatically
Every push to `main` triggers GitHub Actions which builds and publishes the site to `gh-pages`.
Enable **Settings → Pages** to serve from that branch.
