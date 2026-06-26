# Dog Pickle

A very simple static webpage, deployed with GitHub Pages.

## Files

- `index.html` — page markup
- `style.css` — styling
- `script.js` — a little interactivity

## Deploy with GitHub Pages

1. Create a repo on GitHub and push this folder:
   ```bash
   git remote add origin https://github.com/<you>/<repo>.git
   git push -u origin main
   ```
2. On GitHub: **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose branch `main` and folder `/ (root)`, then **Save**.
5. Your site goes live at `https://<you>.github.io/<repo>/` within a minute or two.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.
