# Conblox

A classic-era game-discovery website concept, rebuilt as an original static frontend for GitHub Pages.

## Included
- 2016-inspired blue navigation and left sidebar
- Home, Games, Catalog, Develop, Profile, Messages and Friends views
- Search, category filters and interactive game detail dialogs
- Responsive desktop and mobile layouts
- Demo-only sign-in and sign-up dialogs

## Deploy
The workflow at `.github/workflows/pages.yml` publishes the repository root on every push to `main`. In GitHub, open **Settings → Pages** and select **GitHub Actions** as the source.

## Important limitations
This is a static frontend. It does not include real accounts, a database, messaging, purchases, an avatar inventory, game servers or a playable game client. Demo buttons explain these limitations and do not send or store credentials.

## About the referenced 2016 source
The repository at https://github.com/SANS3R66/roblox-2016-source-code contains a large native C++ Windows client/Studio solution. Its build guide requires Visual Studio and Win32 build configurations; it is not browser JavaScript or a website that GitHub Pages can run. GitHub currently reports no declared repository licence. This project therefore recreates the classic-era web experience with original HTML, CSS and JavaScript rather than redistributing that source code.
