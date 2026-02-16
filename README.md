# Albert's Blog

A simple static blog. No frameworks, no build step.

## Writing a new article

1. Copy `template.html` into `articles/` with a slug name (e.g., `my-new-post.html`).
2. Replace `ARTICLE TITLE` and `DATE` in the new file.
3. Write your content. Use [markdowntohtml.com](https://markdowntohtml.com) to convert plain text or Markdown into HTML.
4. Add a link to `index.html`.
5. Commit and push.

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then click **Save**.
5. Your site will be live at `https://<username>.github.io/<repo-name>/` within a minute or two.

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000.
