# The Kayasths Studio — website

Static single-page site (no build step, no dependencies). Deploys as-is on GitHub Pages.

## Deploy on GitHub Pages
1. Create a new public repository (e.g. `the-kayasths-studio`).
2. Upload every file in this folder to the repository root (`index.html` must be at the root).
3. Repository → Settings → Pages → Source: "Deploy from a branch" → Branch: `main` → Folder: `/ (root)` → Save.
4. After about a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Update content (all inside `index.html`, in the `<script>` at the bottom)
- Indian packages and prices: the `IN` array. International packages: `IP`; per-market prices: `MK`; care plans: `CARE`.
- FAQ: the `FQ` array. WhatsApp number: the `N` constant.
- Project cards: the `#work` section in the HTML.

## Still to do after you choose a final URL
- Add `<link rel="canonical" href="https://YOUR-URL/">` inside `<head>`.
- Add a `sitemap.xml` and a `Sitemap:` line in `robots.txt`.
- Analytics are not installed. Add them only once you have a real tracking ID and consent setup.
- No form backend exists: the enquiry form opens WhatsApp with a prepared message.
