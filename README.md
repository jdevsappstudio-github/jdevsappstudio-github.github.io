# jdevsappstudio-github.github.io

GitHub Pages site for JDevsAppStudio. Hosted at `https://jdevsappstudio-github.github.io/`.

## Structure

```
/
└── bunku/
    ├── index.html           ← Bunku landing page
    └── privacy-policy.html  ← Bunku privacy policy
```

Each app gets its own folder. Add `/appname/index.html` for a new app.

## Live URLs

| Page | URL |
|---|---|
| Bunku landing page | `https://jdevsappstudio-github.github.io/bunku/` |
| Bunku privacy policy | `https://jdevsappstudio-github.github.io/bunku/privacy-policy.html` |

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

- Privacy policy URL given to Play Console: `https://jdevsappstudio-github.github.io/bunku/privacy-policy.html`
- If you add ads in future, update the Advertising section in `bunku/privacy-policy.html` and bump the "Last updated" date
- Play Store link in `bunku/index.html` uses the real package ID (`com.jdevsappstudio.bunku`) — update the full URL once the app is live on Play Store
