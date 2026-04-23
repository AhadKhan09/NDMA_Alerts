# NDMA Early Warning Site Clone

This workspace contains a direct static mirror of:
https://early-warning-ndma.preview.emergentagent.com/

## Files

- `index.html`
- `static/js/bundle.js`
- `static/js/bundle.js.map`
- `data/alerts.json`
- `data/advisories.json`
- `data/dew-regions.json`
- `data/stats.json`

## Run locally

Serve this folder with any static web server.

Option 1 (Node.js):

```powershell
npx --yes http-server . -p 4173
```

Option 2 (VS Code Live Server extension):

- Open `index.html`
- Start "Open with Live Server"

Then open:

http://127.0.0.1:4173

You can also open direct section URLs:

- http://127.0.0.1:4173/alerts
- http://127.0.0.1:4173/advisories
- http://127.0.0.1:4173/dew

## Notes

- This is a mirrored production frontend build for exact visual and behavior parity.
- App data is now fully local and loaded from the `data/*.json` files in this workspace.
- You can edit the JSON files directly to update alerts, advisories, DEW regions, and dashboard stats.
