# emin.ch (GitHub Pages)

Simple static site for https://emin.ch.

## Deploy

1. Create GitHub repo: `emin.ch` under `emin93`
2. Push files in this directory to that repo
3. In GitHub: **Settings → Pages**
   - Source: `Deploy from a branch`
   - Branch: `main` / `/ (root)`
4. Keep `CNAME` file as-is (`emin.ch`)

## DNS (Cloudflare or your DNS provider)

For apex domain (`emin.ch`), use A records:

- `@` → `185.199.108.153`
- `@` → `185.199.109.153`
- `@` → `185.199.110.153`
- `@` → `185.199.111.153`

For www:

- `www` CNAME → `emin93.github.io`

If using Cloudflare, use **DNS only** (grey cloud) initially until SSL is active on GitHub Pages.
