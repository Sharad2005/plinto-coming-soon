# Plinto Coming Soon

Temporary static landing page for Plinto Studio, hosted with GitHub Pages.

## Files

- `index.html`: main coming-soon page
- `styles.css`: page styling
- `assets/plinto.studio.png`: brand logo
- `CNAME`: custom domain (`plinto.studio`)
- `.nojekyll`: disables Jekyll processing

## GitHub Pages Setup

1. Push this repository to GitHub as `plinto-coming-soon`.
2. In GitHub repository settings, open **Pages**.
3. Set source to **Deploy from a branch**.
4. Select branch **main** and folder **/ (root)**.
5. Confirm custom domain is set to `plinto.studio`.
6. Enable **Enforce HTTPS** once certificate is issued.

## DNS Notes

Set apex domain DNS records to GitHub Pages IPs (via your DNS provider docs):

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Optionally map `www` as CNAME to your GitHub Pages host.
