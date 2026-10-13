# wangzeyuan555.github.io

Static personal homepage served via GitHub Pages, used as the **Homepage URL**
in the OpenReview registration (*Personal Links* section).

## Deployment

1. Create a public GitHub repository named exactly `<your-github-username>.github.io`
   (e.g. `wangzeyuan555.github.io`). The name must match your username **character for character**.
2. Push the contents of this directory to that repository's `main` branch:

   ```bash
   git init
   git add .
   git commit -m "Add personal homepage"
   git branch -M main
   git remote add origin git@github.com:<your-github-username>/<your-github-username>.github.io.git
   git push -u origin main
   ```

3. In the repository: **Settings → Pages → Build and deployment**
   - Source: `Deploy from a branch`
   - Branch: `main`, folder `/ (root)`
   - Save
4. Wait 1–2 minutes. The site is live at `https://<your-github-username>.github.io`.

## Before pushing

Replace the placeholders in `index.html`:

- `Zhiyuan Wang` — your name, spelled exactly as in your paper author list
- `wangzeyuan05@kuaishou.com` — the email registered in OpenReview
- `https://github.com/wangzeyuan555` — your actual GitHub profile URL
- Publications section — your real papers, or delete the section entirely

## Why the email must appear as text

OpenReview requires at least one URL whose page displays **both your name and
your email**. Academic profile sites (Google Scholar, DBLP, ORCID) do not show
an email address, so a self-hosted homepage is the most reliable option.
