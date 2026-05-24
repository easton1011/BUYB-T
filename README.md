# BUYBIT Dashboard

Static trading dashboard website for BUYBIT.

## Local development

Open the HTML files directly in a browser or serve them from a local static web server.

## Screenshot tooling

The repo includes a Playwright screenshot helper for responsive page captures:

```bash
npm install
npm run screenshot
```

Screenshots are saved to `screenshots/`.

## GitHub hosting

1. Create a new repository in your GitHub account.
2. Add the remote in this directory:

```bash
git remote add origin https://github.com/<your-username>/<your-repo>.git
```

3. Push the repository:

```bash
git push -u origin main
```

4. Enable GitHub Pages in repository settings:
   - Source: `main` branch
   - Folder: `/ (root)`

After that, your static site will be hosted at `https://<your-username>.github.io/<your-repo>/`.
