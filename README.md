# Knowledge Site Starter (MkDocs Material)

This is a beautiful, fast, and easy-to-maintain **knowledge website** template powered by **MkDocs Material** and deployed automatically to **GitHub Pages**.

## ✨ Highlights
- Modern, responsive UI with dark/light mode
- Built-in search, tags, and blog
- Mobile-friendly, great typography for Thai & English
- Auto-deploy via GitHub Actions to `gh-pages`

---

## 🚀 Quick Start

1) **Create a new GitHub repository** (public recommended for free GitHub Pages).  
   Example name: `knowledge-site`.

2) **Download this starter**, unzip it, and then push to your repo:
```bash
git init
git remote add origin https://github.com/<YOUR_USERNAME>/knowledge-site.git
git add .
git commit -m "Init knowledge site"
git branch -M main
git push -u origin main
```

3) **Enable GitHub Pages**:  
   - Go to **Settings → Pages**  
   - **Source**: *Deploy from a branch*  
   - **Branch**: `gh-pages` / `(root)`  
   - Save.

4) **Wait for Actions to finish**. Your site will be live at:  
   `https://<YOUR_USERNAME>.github.io/knowledge-site/`

> Tip: To customize the site name, colors, and navigation, edit `mkdocs.yml`.

---

## 🛠 Local Preview (optional)

Install Python 3.10+ and run:

```bash
pip install -r requirements.txt
mkdocs serve
```

Open http://127.0.0.1:8000 to preview changes with hot reload.

---

## 📁 Structure

```
.
├── .github/workflows/gh-pages.yml   # CI/CD to GitHub Pages
├── docs/                            # Your content here
│   ├── index.md                     # Home (Thai + English)
│   ├── guide/                       # Guides
│   ├── blog/                        # Blog posts
│   ├── th/                          # Thai-specific pages
│   └── assets/                      # Images
├── mkdocs.yml                       # Site config
├── requirements.txt                 # Python dependencies
└── README.md
```

---

## 🔧 Customize

- **Logo / Icon**: Replace `docs/assets/logo.svg`.
- **Theme & colors**: See `mkdocs.yml` (`theme:` section).
- **Nav**: Edit `nav:` in `mkdocs.yml` to reorder pages.
- **Blog**: Add Markdown files under `docs/blog/`.

---

## 🧩 Useful links

- MkDocs Material: https://squidfunk.github.io/mkdocs-material/
- MkDocs: https://www.mkdocs.org/

---

Made with ❤️ for Thai & English knowledge sharing.
