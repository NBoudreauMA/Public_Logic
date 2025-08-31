# Public_Logic Launch Site

This is a tiny, production-ready static site for **Public_Logic**.

## Quick Start (GitHub Pages)
1) Create a new GitHub repo, e.g. `public_logic_site`.
2) Upload the contents of this folder.
3) In **Settings → Pages**, set **Branch: `main`** and `/root`. Save.
4) Your site publishes at `https://<your-username>.github.io/<repo>/`.

## Custom Domain (optional)
- Add your domain in **Settings → Pages → Custom domain**.
- Create a CNAME at your DNS host pointing to `your-username.github.io`.

## Editing Text/Pages
- Update copy in the HTML files in the project root (`index.html`, `note.html`, etc.).
- Brand colors are defined in `css/style.css` (`--pl-green`, `--pl-teal`, etc.).
- The logo image lives at `assets/logoA.png` (replace with your own whenever).

## Contact Form (Power Automate)
- Open `contact.html` and replace `FLOW_URL` with your **HTTP trigger** URL from Power Automate.
- Ensure CORS allows your site origin. In the flow, store submissions to SharePoint or send an email.

## Accessibility & SEO
- Semantic HTML, alt text for images, meta description on index.
- Add real content to `note.html` and `about.html` to improve indexing.
- `robots.txt` included.

## File List
- `index.html` — landing page (Launch)
- `note.html` — Field Note_001 scaffold
- `about.html` — company overview
- `framework.html` — VAULT overview
- `contact.html` — Early Access form (Power Automate-ready)
- `404.html`, `robots.txt`
- `css/style.css`, `js/main.js`
- `assets/logoA.png` (simple placeholder)

---

Made with ❤️ for municipal-first builders.
