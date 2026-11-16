# Spruce Goose Productions: App Store public documents

This repository is the one public home for every app's **App Store public documents**: privacy policy, terms of use and support page. It is served by GitHub Pages from `main` at https://gibbyspice.github.io/spruce-goose-apps/.

**What belongs here:** only those public pages (plain HTML, one shared `style.css`). The public contact on every page is sprucegooseproductions@gmail.com.

**What does not belong here:** app code, build files, scripts, keys or anything private. Each app's code lives in its own repository.

| App | Folder | Code repository |
|---|---|---|
| ChessRealm: ELO Trainer | `chessrealm-elo-trainer/` | gibbyspice/chessrealm-trainer |
| ChessRealm: Openings | `chessrealm-openings/` | gibbyspice/chessrealm-openings |
| ChessRealm: Game Study | `chessrealm-game-study/` | gibbyspice/rork-chessrealm--game-study |
| Next Play Baseball | `next-play-baseball/` | gibbyspice/rork-next-play-baseball |

## Rules

- Each app gets a folder with `index.html` (support), `privacy.html` and `terms.html`, and a link in the root `index.html`.
- Write each page from what the app really does (check its code), not from another app's page.
- When an app changes what data it handles, update its privacy page and the effective date in the same change.
- Never rename this repository or a folder: App Store Connect listings and shipped apps link to these URLs, and GitHub Pages does not redirect after a rename.
- Merging to `main` publishes.
