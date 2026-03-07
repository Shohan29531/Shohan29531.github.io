# Md Touhidul Islam — Personal Academic Website

A clean, responsive academic portfolio website ready for GitHub Pages.

## 🚀 Deploy in 2 minutes

1. Create a GitHub repo named **`<your-username>.github.io`**
2. Upload all files from this folder (not the folder itself, just the contents)
3. Go to **Settings → Pages → Source: main branch / (root)**
4. Site goes live at `https://<your-username>.github.io`

---

## 📸 Add your photo

Save your profile photo as **`assets/photo.jpg`** — the home page will automatically display it.

## 📄 Add your CV PDF

1. Copy your CV as **`assets/cv.pdf`**
2. In `cv.html`, uncomment the `<iframe>` block at the bottom to embed it inline

---

## 📁 File structure

```
.
├── index.html          ← Home (about, skills, news)
├── publications.html   ← All papers with links
├── experience.html     ← Work history (NEW)
├── education.html      ← Degrees
├── portfolio.html      ← Project cards by category
├── cv.html             ← CV download + embed
├── assets/
│   ├── style.css       ← All styles + CSS variables
│   ├── photo.jpg       ← Add your photo here
│   └── cv.pdf          ← Add your CV here (optional)
└── README.md
```

## 🎨 Customizing colors

Edit the CSS variables at the top of `assets/style.css`:

```css
:root {
  --navy:   #162032;   /* navigation bar, headings */
  --accent: #c0622a;   /* links, highlights, borders */
  --bg:     #f8f7f4;   /* page background */
}
```

## ✏️ Editing content

| File | What to update |
|------|---------------|
| `index.html` | Photo, contacts, about text, skills, news items |
| `publications.html` | Add / remove papers |
| `experience.html` | Job roles and bullet points |
| `education.html` | Degrees, institutions, GPAs |
| `portfolio.html` | Project cards, GitHub/paper links |
| `cv.html` | CV download link |
