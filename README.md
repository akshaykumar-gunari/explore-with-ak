# Explore with AK

A personal knowledge base of everything technical — built in public, one topic at a time.

Live site → [explore-with-ak](https://akshaykumar-gunari.github.io/explore-with-ak/)

---

## What's covered

- **Linux & Kernel** — how Linux works under the hood, kernel internals, system calls, and the shell
- **Mathematics** — the math that powers computing, from discrete math to linear algebra and beyond
- **AI & Machine Learning** — concepts, architectures, papers, and experiments

---

## Built with

- [MkDocs](https://www.mkdocs.org) — static site generator for documentation
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) — theme

---

## Run locally

**Prerequisites** — Python 3.8+
```bash
# Install dependencies
pip install -r requirements.txt

# Start local dev server
mkdocs serve
```

Open `http://127.0.0.1:8000` in your browser. The site hot-reloads as you edit.

---

## Deploy

Deploys automatically to GitHub Pages on every push to `main` via GitHub Actions.

To deploy manually:
```bash
mkdocs gh-deploy --force
```

---

## Repo structure

explore-with-ak/
├── .github/
│   └── workflows/
│       └── deploy-docs.yml   # auto-deploy on push to main
├── docs/
│   ├── index.md              # home page
│   ├── programming/
│   ├── linux/
│   ├── mathematics/
│   └── ai-ml/
├── .gitignore
├── mkdocs.yml
├── requirements.txt
└── README.md