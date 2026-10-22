# Outer Ring — Testing & Research (website)

Live site: https://outerringresearch.com — GitHub Pages from this repo (`main`, root).

- `index.html` — the single-page site (no build step).
- `assets/outer-ring-logo-flat.png` — flat working master (header mark, favicon).
  **Permanent asset:** email signatures reference
  `https://outerringresearch.com/assets/outer-ring-logo-flat.png` — do not move or rename.
- `assets/outer-ring-logo-seal.png` — bevel+emboss display version (hero + seal of approval).
- `CNAME` — custom domain `outerringresearch.com`.

Brand spec: green #00B050, gray #58595B. Outer Ring is a division of Unlimited Apps.
Mail for this domain runs on Migadu (MX/SPF/DKIM/DMARC at Porkbun) — never touch those
records when changing web DNS; only the apex A/AAAA and `www` CNAME belong to this site.
