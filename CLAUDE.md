# Site Directory — project notes for Claude

Public repo. Keep this file free of personal details and anything secret.
Full history in the private notes repo (`twoseam/claude-notes`,
`projects/Site Directory/`).

## What it is
- One-page launcher listing every site Michael hosts.
- Live: https://twoseam.github.io (this repo, `index.html` at root).
  User-site repo: Pages is automatic. No custom domain.

## Sites listed
- JotList (jotlist.io), Cycles Looper (cycleslooper.com), Flight Log,
  Mike & Xan (mikeandxan.com), Mileage, Wiggler (wiggler.app).
- Mileage web app is retired — remove its row during the cleanup.
- New site with Pages? Add a row. Custom domain → use it; otherwise
  `twoseam.github.io/<repo>/`.
- `sveltia-cms-auth` is tooling, not a site. Keep it off.

## Design (locked)
- "Minimal and stark, no fluff, no designed-by-Claude vibes."
- Monochrome. Accent is bark grey (`#4a4a46` light / `#b8b5ac` dark).
  NOT a color. Don't add a chromatic accent without asking.
- System fonts only. `ui-monospace` for labels/domains, system sans for taglines.
- One column, one bordered button per site.
- Light/dark toggle saved per browser (`localStorage`). Restore script runs
  before `<style>` to avoid a flash.
- No header/footer chrome. No about section.

## Rules
- Don't invent taglines. Ask Michael.
- Commit and push before ending any session.
