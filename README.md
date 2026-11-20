# Deploy Diary

A tiny static web app used to learn the GitHub push-to-deploy workflow.

- `index.html` — the whole app
- `.github/workflows/deploy.yml` — GitHub Actions workflow: every push to
  `main` republishes the site to GitHub Pages

## The deployment loop

```
edit files → git add → git commit → git push → Actions builds → site is live
```
