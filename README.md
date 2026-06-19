# Snowfall Point Lookup

GitHub-ready Cloudflare Worker project.

## Files

- `index.js` — complete browser application and NOAA relay
- `wrangler.jsonc` — Cloudflare Worker configuration

## Deploy through GitHub and Cloudflare

1. Create a GitHub repository.
2. Upload `index.js`, `wrangler.jsonc`, and this README.
3. In Cloudflare Workers & Pages, import the GitHub repository.
4. Use `main` as the production branch.
5. Leave the build command blank.
6. Use `npx wrangler deploy` as the deploy command.
7. Deploy and open the generated `.workers.dev` URL.
