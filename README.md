# Personal site — Sree Rama Vamsidhar Saraswathula

A single self-contained `index.html` (fonts loaded from Google Fonts CDN, no build step, no dependencies).

## Host it free on GitHub Pages

1. Create a new repository on GitHub. For a site at `https://<your-username>.github.io`, name the repo exactly `<your-username>.github.io`. For a project-style URL instead (`https://<your-username>.github.io/site-name`), any repo name works.
2. Upload `index.html` to the repo root (drag-and-drop on the GitHub web UI, or via git — see below).
3. Go to the repo's **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
6. Wait ~1 minute, then visit the URL GitHub shows on that page.

### Via git (command line)

```bash
git init
git add index.html README.md
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Then enable Pages as in steps 3–6 above.

## Using a custom domain (optional)

In **Settings → Pages → Custom domain**, enter your domain and add a `CNAME` record at your DNS provider pointing to `<your-username>.github.io`. GitHub will add a `CNAME` file to the repo automatically.

## Editing later

Everything — copy, links, publication list — lives in the one `index.html` file. Search for the section you want (`id="publications"`, `id="updates"`, etc.) and edit the text directly; no rebuild step needed.
