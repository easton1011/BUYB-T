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
   - Source: `main` branch or `gh-pages` branch
   - Folder: `/ (root)`

After that, your static site will be hosted at `https://<your-username>.github.io/<your-repo>/`.

## Custom domain

To use your own custom domain:

1. Replace the contents of `CNAME` with your real domain, for example:

```text
your-custom-domain.com
```

2. Commit and push:

```bash
git add CNAME
git commit -m "Add custom domain"
git push
```

3. In your domain registrar, configure DNS:
   - For `www.your-custom-domain.com`, add a `CNAME` record to `easton1011.github.io`
   - For root domains like `your-custom-domain.com`, add GitHub Pages `A` records:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`

4. In GitHub Pages settings, set the custom domain to `your-custom-domain.com` and enable HTTPS.
