# Deploy Guide - Base10 · 1-to-10s Series A Prioritization

The site lives at: https://ade-b10.github.io/series-a-prioritization/
Password: `Base10Automation!`

## Re-encrypting after edits

```bash
cd /Users/ade/Desktop/Urizen/series-a-prioritization-deploy
# Edit source/Series_A_Prioritization.html
./update.sh
git add index.html && git commit -m "Refresh" && git push
```

GitHub Pages re-deploys in ~30s.
