# jdevsappstudio-github.github.io

GitHub Pages site for JDevsAppStudio. Hosted at `https://jdevsappstudio-github.github.io/`.

## Structure

```
/
├── bunku/
│   ├── index.html           ← Bunku landing page
│   └── privacy-policy.html  ← Bunku privacy policy
└── animepedia/
    ├── index.html             ← AnimePedia landing page
    ├── privacy-policy.html    ← AnimePedia privacy policy
    └── terms-of-service.html  ← AnimePedia terms of service
```

Each app gets its own folder. Add `/appname/index.html` for a new app.

## Live URLs

| Page | URL |
|---|---|
| Bunku landing page | `https://jdevsappstudio-github.github.io/bunku/` |
| Bunku privacy policy | `https://jdevsappstudio-github.github.io/bunku/privacy-policy.html` |
| AnimePedia landing page | `https://jdevsappstudio-github.github.io/animepedia/` |
| AnimePedia privacy policy | `https://jdevsappstudio-github.github.io/animepedia/privacy-policy.html` |
| AnimePedia terms of service | `https://jdevsappstudio-github.github.io/animepedia/terms-of-service.html` |

## How to update

1. Edit the file(s) in the relevant folder
2. Commit and push to `main`

```bash
git add .
git commit -m "update: <what you changed>"
git push
```

GitHub Pages rebuilds automatically — changes go live within a few minutes.

## Notes

- Privacy policy URLs given to Play Console:
  - Bunku: `https://jdevsappstudio-github.github.io/bunku/privacy-policy.html`
  - AnimePedia: `https://jdevsappstudio-github.github.io/animepedia/privacy-policy.html`
- If you add/change ads, billing, or data collection, update the matching privacy-policy.html and bump its "Last updated" date
- Play Store links use each app's real package ID (`com.jdevsappstudio.bunku`, `com.jdevsappstudio.animepedia`)
