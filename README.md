# Md Touhidul Islam — GitHub Pages Site

A clean, responsive academic personal website ready to deploy on GitHub Pages.

## 🚀 Quick Setup

1. **Create a new GitHub repo** named `<your-username>.github.io`  
   (e.g. `tshohan.github.io`)

2. **Upload all files** from this folder into the repo (or `git push`)

3. Go to **Settings → Pages → Source: main branch / root**

4. Your site will be live at `https://<your-username>.github.io` within a minute or two.

---

## 📸 Adding Your Photo

1. Save your profile photo as `assets/photo.jpg`
2. The home page will automatically display it

---

## 📄 Adding Your CV PDF

1. Copy your CV as `assets/cv.pdf`
2. In `cv.html`, uncomment the `<iframe>` block at the bottom to embed it inline

---

## 🖊️ Editing Content

| File | What to edit |
|------|-------------|
| `index.html` | Name, contact info, about me, news items |
| `publications.html` | Add / remove publication entries |
| `education.html` | Degrees and institutions |
| `portfolio.html` | Projects, demos, links |
| `cv.html` | CV download link |
| `assets/style.css` | Colors, fonts, layout |

### Changing colors

Open `assets/style.css` and edit the CSS variables at the top:

```css
:root {
  --navy:   #1a2332;   /* nav bar + headings */
  --accent: #b5651d;   /* links + highlights */
  --bg:     #f7f5f0;   /* page background   */
}
```

---

## 📁 File Structure

```
.
├── index.html          ← Home
├── publications.html
├── education.html
├── portfolio.html
├── cv.html
├── assets/
│   ├── style.css       ← All styles
│   ├── photo.jpg       ← Add your photo here
│   └── cv.pdf          ← Add your CV here (optional)
└── README.md
```
