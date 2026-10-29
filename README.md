# Kevin Runs Boston — website

A responsive single-page fundraising website for kevinrunsboston.com.

## Publish using GitHub Pages
1. Create a public GitHub repository (for example `kevin-runs-boston`).
2. Upload `index.html`, `styles.css`, `script.js`, `config.js`, and the `assets` folder to the repository root.
3. In **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
4. Once Pages is live, add `kevinrunsboston.com` in **Settings → Pages → Custom domain**.
5. At your domain registrar, create four A records for the apex (`@`): `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`. Optionally create `www` CNAME to `<your-github-username>.github.io` (replace placeholder). Remove conflicting apex A/AAAA records. Enable **Enforce HTTPS** when available.

## Update the website
Edit **config.js** in GitHub, then commit. Change `raised` to the current amount collected, edit `events` URLs as they become available, and add entries under `trainingUpdates`. The $12,000 goal is editable too.

**Important:** The donation tracker is *manual*, not automatically synced with GivenGain. It initially displays $0 as a placeholder, **not** a verified current total. Update it before publishing.

The auction and event links are intentionally inactive until you provide URLs. The countdown targets April 19, 2027, 10:28 a.m. **Boston daylight time (EDT)**. The requested time was labeled EST in the brief, but Boston observes EDT in April.

This independent fundraising site uses user-supplied event and foundation imagery. No Boston Marathon logo is embedded; official logos and marks may require permission for public use.
