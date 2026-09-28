# Product Portfolio

A single-page product portfolio — hero, project case studies, experience timeline, skills, and contact. No build step, no dependencies.

## Structure

```
index.html          # content (hero, work, experience, skills, contact)
style.css           # styling (auto light/dark)
Om_Shah_Resume.pdf   # linked from the "Resume" button in the hero
```

## Customize

- Edit copy directly in `index.html` — each project is one `<article class="project">` block; each experience entry is one `.timeline-item`.
- Swap in real GitHub/live links on the `.project-link` anchors (Aegis AI and the Amazon Rufus redesign don't have public repos linked yet — add them if you make the Figma files public, or drop the link entirely).
- Replace `Om_Shah_Resume.pdf` with an updated resume any time — keep the filename or update the link in `index.html`.
- Colors, spacing, and card style live at the top of `style.css` under `:root`.

## Deploy with GitHub Pages

1. Push this repo to GitHub (or upload these files to your existing repo, replacing the old ones).
2. Go to **Settings → Pages**.
3. Under "Build and deployment," set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Your site will be live at `https://<username>.github.io/<repo-name>/`.

To use a custom domain, add a `CNAME` file with your domain name and configure DNS per [GitHub's docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
