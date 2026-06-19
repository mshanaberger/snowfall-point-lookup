# Snowfall Point Lookup — Relay Fix 1.1

This update fixes the NOAA relay-path mismatch.

## Updating an existing GitHub deployment

1. Replace the existing `index.js` in your repository with this `index.js`.
2. Commit the change to `main`.
3. Cloudflare should redeploy automatically.
4. Open `/api/health` on your Worker URL and confirm `version` is `1.1-relay-fix`.
5. Reload the application, preferably with a hard refresh.

The browser and Worker now both use:

`https://www.nohrsc.noaa.gov/snowfall_v2/data/`
