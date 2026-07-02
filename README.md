# V1K1NG316.github.io

My personal site, served by **GitHub Pages** straight from this repo.

Live URL (once published): **https://v1k1ng316.github.io**

## What's in here

| File | Purpose |
| --- | --- |
| `index.html` | Home page (hero, about, projects, contact) |
| `style.css` | Styling with light/dark theme variables |
| `script.js` | Footer year + persistent theme toggle |
| `404.html` | Custom "page not found" page |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (skip Jekyll) |

No build step. It's plain HTML/CSS/JS — GitHub Pages just serves the files.

## Publish it (one-time setup)

Because the repo is named `V1K1NG316.github.io` (matches your username),
GitHub Pages treats it as your **user site** and publishes automatically.

```bash
# From inside this directory:
git init
git add .
git commit -m "Initial GitHub Pages site"
git branch -M main

# Create the repo on github.com named exactly:  V1K1NG316.github.io
# Then:
git remote add origin https://github.com/V1K1NG316/V1K1NG316.github.io.git
git push -u origin main
```

Then in the repo on GitHub:

1. **Settings → Pages**
2. Under **Build and deployment**, set **Source** = `Deploy from a branch`
3. Set **Branch** = `main` and folder = `/ (root)` → **Save**
4. Wait ~1 minute, then visit **https://v1k1ng316.github.io**

## Editing later

Just edit the files and push. GitHub Pages rebuilds automatically on every push
to `main`. Reference: <https://docs.github.com/en/pages>.

## Local preview

Any static file server works. Easiest:

```bash
# Python 3
python3 -m http.server 8000
# then open http://localhost:8000
```

