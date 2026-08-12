# Private Greenhouse

Gateway page using the TC Controls **split v4** format (intro + three industry tiles: BMS, CEA, Turnkey Greenhouses).

Self-contained for local preview and Cloudflare Pages.

## Preview

Open `index.html` with Live Server, or:

```bash
npx serve .
```

## Deploy

```bash
npx wrangler pages project create private-greenhouse --production-branch main
npx wrangler pages deploy . --project-name private-greenhouse
```
