# Beast Pit site

Static pages for the Beast Pit Play Store listing: a landing page and the privacy policy.

- `index.html`: landing page (`style.css`, `img/` and `fonts/` are built by `python3 -I tools/build_site_art.py ../beast-pit-site` in the game repo). The trailer link (https://youtu.be/mt8stKIenBo) is in three places in `index.html`
- `privacy.html`: privacy policy (paste its public URL, e.g. `https://<user>.github.io/<repo>/privacy.html`, into the Play Console)

Keep `privacy.html` in sync with `docs/PRIVACY_POLICY.md` in the game repo.

Publish with GitHub Pages: push this repo to GitHub, then Settings > Pages > deploy from branch `main`, folder `/ (root)`.
