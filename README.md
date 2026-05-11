# hush-legal — GitHub Pages site for Hush · Daily Journal

Public-facing Privacy Policy + Terms of Service for the Hush iOS app.
Required by Apple App Store Connect (Privacy Policy URL field).

## Files

- `index.html` — landing page (just lists Privacy + Terms links)
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service

## How to publish

1. Create a new public GitHub repo named `hush-legal`
2. Upload these three files to the repo root
3. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save
4. After ~1 minute, site goes live at:
   `https://<your-github-username>.github.io/hush-legal/`
5. Specific URLs:
   - Privacy: `https://<username>.github.io/hush-legal/privacy.html`
   - Terms:   `https://<username>.github.io/hush-legal/terms.html`

## App Store Connect

Paste the Privacy URL in:
**App Store Connect → App Information → Privacy Policy URL**

(Same URL pattern goes in Subscription Group → Terms link if Apple asks.)

## Updating

Edit the HTML files locally, commit, push. GitHub Pages auto-republishes.
Keep `Last updated` date in sync between these HTML files and the in-app copy at
`Projects/journal-app/src/data/legal.ts`.
