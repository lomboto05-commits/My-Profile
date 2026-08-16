# christianlomboto.ie — portfolio

Single-page portfolio site. No build step, no dependencies — pure HTML/CSS/JS.

## Deploy (Vercel)
1. Push this repo to GitHub (e.g. `lomboto05-commits/portfolio`).
2. Vercel → Add New Project → import the repo → Framework preset: **Other** → Deploy.
3. Project → Settings → Domains → add `christianlomboto.ie` and `www.christianlomboto.ie` (set www to redirect to root). Add the DNS records Vercel shows into Cloudflare (set the records to **DNS only / grey cloud**).

## Structure
- `index.html` — the whole site (styles, scripts inline)
- `cv/Christian_Lomboto_CV.pdf` — CV download

## Editing
All copy lives in `index.html`. Metric values in the charts are set via `data-count` / `data-w` / `data-h` attributes and one `data` array in the sparkline script — update those if project numbers change.
