# S. Karthik Sriram Portfolio

Placement-ready static portfolio for software engineering internships and entry-level roles.

## Highlights

- Responsive HTML, CSS, and JavaScript portfolio
- Light and dark theme toggle with saved preference
- Recruiter-focused project descriptions
- SEO metadata, Open Graph tags, sitemap, robots file, and web manifest
- GitHub Pages deployment workflow

## Local Preview

Open `index.html` directly in a browser.

## Deploy to GitHub Pages

This folder is currently a static site. To publish it at `https://kxrtik250.github.io/karthik-portfolio/`, push it to a GitHub repository named `karthik-portfolio` under the `kxrtik250` account, then enable Pages from GitHub Actions.

```powershell
git init
git add .
git commit -m "Make portfolio placement ready"
git branch -M main
git remote add origin https://github.com/kxrtik250/karthik-portfolio.git
git push -u origin main
```

After pushing, open the repository on GitHub, go to `Settings > Pages`, and set the source to `GitHub Actions`.

## Update the Live Site

After editing the portfolio locally, push the latest changes:

```powershell
git add .
git commit -m "Update portfolio from resume"
git push
```

GitHub Pages will redeploy automatically from the workflow.
