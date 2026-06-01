# cloudpaw.gg placeholder

Minimal static placeholder website for Cloudflare Pages.

## Files

- `index.html`
- `styles.css`

## Deploy to Cloudflare Pages

1. Push this folder to a GitHub repository.
2. In Cloudflare Dashboard, go to **Workers & Pages** -> **Create** -> **Pages** -> **Connect to Git**.
3. Select the repository.
4. Build settings:
   - Framework preset: `None`
   - Build command: *(leave empty)*
   - Build output directory: `/`
5. Deploy.
6. In your Pages project, open **Custom domains** and add `cloudpaw.gg` (and optionally `www.cloudpaw.gg`).
7. Since DNS is already on Cloudflare, confirm the generated DNS records are present and active.

