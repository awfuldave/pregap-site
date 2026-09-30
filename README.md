# pregap.app

The website for [Pregap](https://pregap.app), the audio CD burner for the Mac:
the home page, [guides](https://pregap.app/guides.html),
[help](https://pregap.app/help.html) and the
[privacy policy](https://pregap.app/privacy.html).

This repo is the website: edit the files here, commit, and push to `main`.
GitHub Pages serves them as they are at **pregap.app** (`.nojekyll`: no build step).

- **Preview:** `python3 -m http.server 8765`, then open http://localhost:8765.
- **Stylesheet changes:** Pages lets browsers cache `style.css` for ten minutes,
  so every page links it as `style.css?v=<hash>`. After changing it, give every
  page the new hash: `shasum style.css | cut -c1-8`.
- **Copy:** no em dashes anywhere on the site.
- **Screenshots:** made in the app's repo; copy them into `img/`.

Questions or problems: [support@pregap.app](mailto:support@pregap.app)
