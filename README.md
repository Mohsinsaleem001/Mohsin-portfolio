[README.md](https://github.com/user-attachments/files/30344205/README.md)
# Mohsin Saleem — Portfolio Website

A single-file, static portfolio site (HTML/CSS/JS only — no build step needed).

## Deploy free on GitHub Pages

1. Go to https://github.com and create a **new repository** named exactly:
   `mohsin-saleem.github.io`
   (replace `mohsin-saleem` with your actual GitHub username — this exact naming pattern gives you a free live URL automatically)

2. Upload `index.html` from this folder into that repository
   (use "Add file → Upload files" on the GitHub website, or via Git — see below)

3. Go to the repo's **Settings → Pages**. Under "Build and deployment", set:
   - Source: `Deploy from a branch`
   - Branch: `main` / `root`
   - Save

4. Wait 1–2 minutes, then your site will be live at:
   `https://<your-username>.github.io`

### Deploying via Git (command line)

```bash
git init
git add index.html
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```

## Custom domain (optional, still free)

If you later buy a domain (e.g. mohsinsaleem.com), add a `CNAME` file with the domain name inside the repo, and point your domain's DNS to GitHub Pages — no hosting cost, only the domain registration fee.

## Editing content

Everything is in `index.html` — text, styles, and a small script are all in one file. To update:
- Project links → search for `port-card` blocks
- Experience/bullets → search for `tl-item` blocks
- Contact info → search for `contact-list`
