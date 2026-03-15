# kabir08.github.io

Personal academic portfolio and research showcase for Kabir Potdar.

## 🚀 Setup (one-time)

1. **Create the repo** on GitHub: name it exactly `Kabir08.github.io`
2. **Clone it locally**, then copy all these files into it
3. In repo Settings → Pages → Source: set to **`main` branch / `/ (root)`**
4. Your site will be live at **https://kabir08.github.io** in ~2 minutes

## 📝 How to edit content

### Add / edit a publication
Open `index.md` and find the block starting with `<!-- ── PUBLICATION 1`. Fill in:
- `pub-title` — your paper title
- `pub-authors` — author list (your name is already bolded)
- `pub-venue` — conference, workshop, or journal name
- `pub-badge` class — change to `pub-badge--conference` or `pub-badge--workshop` if needed
- `pub-abstract` — one or two sentences
- `pub-links` `href` attributes — arXiv URL, PDF, code repo

To add a second paper, duplicate the entire `<article class="pub-card">` block.

### Add / edit a project
Open `index.md` and find `<!-- ── PROJECT CARD`. Fill in:
- `<h3>` — project name
- `<p>` — description (2–3 sentences)
- `project-tag` — category label (e.g. `LLM Efficiency`, `RAG`, `Kaggle`)
- GitHub link `href`
- `project-tech` spans — tech stack tags

To add more projects, duplicate any project card block.

### Update personal info
Edit `_config.yml` for name, email, social handles.

## 🗂 File structure
```
kabir08.github.io/
├── _config.yml        ← site metadata & social links
├── index.md           ← ALL main page content (edit this!)
├── Gemfile
├── _layouts/
│   └── default.html   ← HTML shell (rarely needs editing)
├── _includes/
│   ├── nav.html
│   ├── footer.html
│   └── icons/         ← SVG icons
└── assets/
    ├── css/main.css   ← all styles
    └── js/main.js     ← scroll & nav behaviour
```

## 🔧 Local preview (optional)
```bash
gem install bundler
bundle install
bundle exec jekyll serve
# → open http://localhost:4000
```
