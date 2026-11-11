# Navi Creative Agency portfolio

A standalone static website. No build step, subscriptions, API keys, or server required.

## Publish on GitHub Pages

1. Create a public GitHub repository named `navi-portfolio`.
2. Upload the contents of this folder into the repository root. Keep `index.html` and `assets/` beside each other; do not upload the ZIP itself.
3. Commit the files to the `main` branch.
4. Open Settings > Pages. Under Build and deployment, select Deploy from a branch.
5. Select `main` and `/(root)`, then Save.
6. GitHub will display the website address after deployment. A project repository normally uses `https://YOUR-USERNAME.github.io/navi-portfolio/`.

For a custom domain, set it in Settings > Pages and configure its DNS using GitHub's instructions:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Edit the portfolio

Edit `index.html` to change text, project links, categories, or styling. Replace images in `assets/` while keeping filenames, or update the matching image paths in HTML. All asset paths are relative, so the website works under a repository subpath or on a custom domain.

## Local preview

Open `index.html` in a browser, or run `python3 -m http.server 8000` in this folder and visit http://localhost:8000.

## Project links

- Renon Investment: https://renon.co.zw/
- Dr. Jose Sax: https://josesax.com/
- Fintch Accounting: https://fintchaccountants.com/
- Leadership Technologies: https://www.leadership-tech.com/

No platform branding, tracking scripts, hosted-platform configuration, or credentials are included in this package.
