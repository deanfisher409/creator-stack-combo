# Creator Stack Combo — GitHub Pages hosting (for TikTok domain verification)

This folder is ready to push to GitHub Pages. It contains the same three public pages, renamed for Pages:

- index.html — website homepage (was website.html)
- terms.html — Terms of Service
- privacy.html — Privacy Policy
- icon-1024x1024.png — 1024x1024 app icon

## How to publish (on the Mac, or in GitHub web UI)

1. Create a public repo on GitHub, e.g. `creator-stack-combo` (or any name).
2. Upload all files in this folder to the repo root.
3. In the repo: Settings → Pages → Source: Deploy from a branch → Branch: main, folder: / (root) → Save.
4. Wait 1-2 minutes. Your site will be at:
   https://<your-github-username>.github.io/creator-stack-combo/
   - Website: https://<your-github-username>.github.io/creator-stack-combo/
   - Terms: https://<your-github-username>.github.io/creator-stack-combo/terms.html
   - Privacy: https://<your-github-username>.github.io/creator-stack-combo/privacy.html
5. Paste THOSE three URLs into TikTok (not the muse.ai ones).

## TikTok domain verification — do this in the TikTok portal

TikTok will still mark the URLs as "not verified" until you prove you control the domain. You cannot verify muse.ai — you do not control it.

In TikTok Developer Portal, next to the Website / Terms / Privacy fields, click Verify. TikTok will give you ONE of these (copy it exactly, do not invent it):
- Option A — DNS TXT record: add a TXT record to your domain's DNS with the value TikTok shows, then click Verify in TikTok.
- Option B — Verification file: download the file TikTok provides (e.g. tiktok-developers-site-verification.txt), upload it to the repo root alongside index.html, wait for Pages to redeploy, then click Verify in TikTok.

For GitHub Pages, Option B (file) is easiest — no DNS access needed. The file must be at the site root, e.g.:
https://<your-github-username>.github.io/creator-stack-combo/tiktok-developers-site-verification.txt

Note: if you use a custom domain instead of github.io, use the DNS TXT method on that domain's DNS.

## After verification

Once TikTok shows the domain as Verified, the "This URL is not verified" error goes away and the app form can save (once the demo video is also uploaded — see demo-video-script.txt in the main submission zip).
