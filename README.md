# Clan War Results

This repository hosts clan war analysis reports on GitHub Pages.

## How to Deploy

1. Export your clan war analysis as HTML from the Tournament Pro app
2. Copy the exported HTML file to this repository as `index.html`
3. Commit and push:

```bash
git add index.html
git commit -m "Update clan war analysis"
git push origin main
```

4. Your report will be available at: https://harlickwin.github.io/warresults/

## Automated Deployment

You can use the deployment script from the tournament-pro directory:

```bash
node scripts/deploy-to-github-pages.js path/to/exported-file.html
```

This will automatically copy the file, commit, and push to GitHub Pages.

## GitHub Pages Setup

Make sure GitHub Pages is enabled in your repository settings:
1. Go to Settings > Pages
2. Source: Deploy from a branch
3. Branch: main / (root)
4. Save

Your site will be published at https://harlickwin.github.io/warresults/
