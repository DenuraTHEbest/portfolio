# Denura Nimsith — Portfolio

Personal portfolio site. Single static page, no build step required.

## Run locally

Just open `index.html` in a browser, or serve it:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy — GitHub Pages (recommended, free)

1. Push this folder to a GitHub repository (see commands below).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Branch: `main`, folder: `/ (root)`. Save.
5. After a minute or two, the site is live at:
   `https://denurathebest.github.io/<repo-name>/`

## Deploy — alternatives

- **Netlify Drop**: go to https://app.netlify.com/drop and drag this folder in — instant live URL, no account needed.
- **Vercel**: `npx vercel` from inside this folder (requires a free Vercel account).
