# PhotoSorter OAuth branding site

Static pages for the Google Cloud OAuth consent screen (home, privacy, terms).

Published URL (GitHub Pages):

- Home: https://justbuildcreate.github.io/photosorter/
- Privacy: https://justbuildcreate.github.io/photosorter/privacy.html
- Terms: https://justbuildcreate.github.io/photosorter/terms.html

## Publish (one-time)

1. On GitHub (account **JustBuildCreate**), create a **public** repo named `photosorter` (empty, no README).
2. From this folder:

```powershell
cd C:\dev\PhotoSorter\site
git init
git add index.html privacy.html terms.html README.md
git commit -m "OAuth branding pages for Google Cloud consent screen."
git branch -M main
git remote add origin https://github.com/JustBuildCreate/photosorter.git
git push -u origin main
```

3. GitHub → repo **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)` → Save
4. Wait a minute, then open https://justbuildcreate.github.io/photosorter/

## Google Cloud Console (GPSMap)

On OAuth Branding / consent screen:

| Field | Value |
|-------|--------|
| App home page | `https://justbuildcreate.github.io/photosorter/` |
| Privacy policy | `https://justbuildcreate.github.io/photosorter/privacy.html` |
| Terms of service | `https://justbuildcreate.github.io/photosorter/terms.html` |
| Authorized domains | `github.io` |

If Google asks to verify the domain, use [Search Console](https://search.google.com/search-console) for `justbuildcreate.github.io` with the same Google account that owns the Cloud project.

Then **Publish app** → In production, and Sign in again in PhotoSorter Settings → Google.
