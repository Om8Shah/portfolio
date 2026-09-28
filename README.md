# Portfolio

A minimal single-page portfolio site — large type, a short bio, two project rows, and three links. No build step, no dependencies.

## Structure

```
index.html   # content
style.css    # styling (auto light/dark)
```

## Customize

- Edit the name, bio, and links directly in `index.html`.
- Swap in your own project rows under the `.projects` section.
- Colors and spacing live at the top of `style.css` under `:root`.

## Deploy with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under "Build and deployment," set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Your site will be live at `https://<username>.github.io/<repo-name>/`.

To use a custom domain, add a `CNAME` file with your domain name and configure DNS per [GitHub's docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
