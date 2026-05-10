# FUSE Website

Public GitHub Pages site for FUSE, an independent mobile chain reaction puzzle
game by Gaborandi.

Live target:

- Home: <https://gaborandi.github.io/fuse-privacy/>
- Privacy: <https://gaborandi.github.io/fuse-privacy/privacy/>
- Terms: <https://gaborandi.github.io/fuse-privacy/terms/>
- Support: <https://gaborandi.github.io/fuse-privacy/support/>

This repository hosts the public website, privacy policy, terms, support page,
theme imagery, and gameplay screenshots referenced by the iOS app and App Store
metadata. The game source remains in `/Users/ahmedalmeldin/Documents/Fuse`.

## Local Preview

From the game source workspace:

```bash
python3 -m http.server 4177 --directory website
```

Then open <http://127.0.0.1:4177/>.

## Release Notes

- Keep all public pages aligned with the actual shipping behavior of the app.
- Do not claim there are no ads, analytics, consent flows, or purchases while
  those systems remain part of the release build.
- Use English as the source of truth unless complete translations are added for
  every public legal page.
