# Base10 · 1-to-10s Series A Prioritization (Password-Protected GitHub Pages)

Series A leaning-in prioritization across the 1-to-10s sheet. Ranked top-12 with bull/bear per. Internal Base10.

Live URL: https://ade-b10.github.io/series-a-prioritization/
Password: `Base10Automation!`

## What's here

- `index.html` - encrypted page (committed to GitHub)
- `source/Series_A_Prioritization.html` - unencrypted source (gitignored)
- `update.sh` - re-encrypt + push helper
- `.staticrypt.json` - salt (DO NOT change; password hash depends on it)

## Update workflow

1. Edit the source HTML at `source/Series_A_Prioritization.html`
2. `./update.sh` (re-encrypts using the committed salt)
3. `git add index.html && git commit -m "Refresh" && git push`

GitHub Pages auto-deploys in ~30 seconds.
