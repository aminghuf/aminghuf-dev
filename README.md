# aminghuf.dev

Personal landing page / CV site. Plain HTML, CSS and JS — no build step.

## Structure

- `index.html` — page content
- `style.css` — styling
- `script.js` — nav toggle + scroll-reveal
- `assets/Amin_G_Resume.pdf` — downloadable CV (linked from the hero section)
- `CNAME` — custom domain for GitHub Pages

## Editing

Just edit `index.html` / `style.css` directly and push — GitHub Pages redeploys automatically.

## Deployment (GitHub Pages)

1. Push this repo to GitHub.
2. Repo Settings → Pages → Source: deploy from branch `main`, folder `/ (root)`.
3. Repo Settings → Pages → Custom domain: `aminghuf.dev` (the `CNAME` file already sets this).
4. At your domain registrar, point DNS at GitHub Pages:
   - `A` records for the apex domain (`aminghuf.dev`) to GitHub's Pages IPs:
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - or a `CNAME` record if using a `www` subdomain instead.
5. Enable "Enforce HTTPS" once DNS propagates.
