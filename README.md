# jdevsappstudio-github.github.io

Studio hub for JDevsAppStudio. Hosted at `https://jdevsappstudio.com/` (custom domain via the
`CNAME` file). Each app now has its own dedicated repo + subdomain — see below.

## Structure

```
/
├── index.html    ← Studio hub (links out to AnimePedia + Bunku)
├── CNAME         ← jdevsappstudio.com
├── bunku/        ← LEGACY, see note below
└── animepedia/   ← LEGACY, see note below
```

## Live URLs

| Page | URL |
|---|---|
| Studio hub | `https://jdevsappstudio.com/` |
| AnimePedia (own repo/domain) | `https://animepedia.jdevsappstudio.com/` — see `AnimePedia-web` repo |
| Bunku (own repo/domain) | `https://bunku.jdevsappstudio.com/` — see `Bunku-web` repo |

## How to update

1. Edit `index.html`
2. Commit and push to `main`

```bash
git add .
git commit -m "update: <what you changed>"
git push
```

GitHub Pages rebuilds automatically — changes go live within a few minutes.

## Notes

- **`bunku/` and `animepedia/` are legacy, not deleted on purpose.** Both apps moved to their own
  repos (`AnimePedia-web`, `Bunku-web`) with their own subdomains, because GitHub Pages only
  supports one custom domain per repo — this repo couldn't serve two different subdomains itself.
  The old `jdevsappstudio-github.github.io/animepedia/...` and `.../bunku/...` URLs are kept alive
  here as a fallback (Play Console still points at the old AnimePedia privacy-policy URL until
  that's updated to the new domain) — don't delete these folders until Play Console's URLs are
  confirmed updated and re-crawled.
- A `/blog/` directory could live at the studio level too (cross-app posts), separate from each
  app's own future `/blog/`.
