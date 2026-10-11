# Charlie Kelley — portfolio

A plain static site (HTML + one CSS file) for GitHub Pages. No build step.

```
index.html            Home: one-liner, work, approach, about
lead-scoring.html     Case study
ai-insights.html      Case study
report-viewer.html    Case study
assets/style.css      All styles
assets/img/           Screenshots (.webp)
Charlie-Kelley-Resume.pdf
```

## Before you publish

1. **LinkedIn:** done.
2. **Resume:** done.
3. **Screenshots:** check that every image in `assets/img/` is OK to show publicly.

## Put it on GitHub Pages

1. On github.com, create a new **public** repository. Naming it `<your-username>.github.io` makes the site live at `https://<your-username>.github.io`.
2. In Terminal:
   ```
   cd ~/Documents/portfolio
   git init
   git add .
   git commit -m "Portfolio v1"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**. Under "Build and deployment," choose **Deploy from a branch**, then **main** and **/ (root)**, and save. The site goes live in a minute or two.

## Adding a case study later

Copy one of the case-study HTML files, change the text and images, then add a card for it in the `#work` section of `index.html`.
