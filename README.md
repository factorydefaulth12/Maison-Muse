# Maison Muse · Connected Universe Prototype

A responsive browser prototype for Maison Muse: one persistent Muse across four connected pillars.

## Play locally
1. Download this repository or its `index.html` file.
2. Open `index.html` in a modern browser.
3. Customize your Muse, explore the four pillars, save outfits, make story choices, and manage a sample household.

## Included
- **Muse Life:** home atmosphere, energy and mood actions, household members, daily intention.
- **Muse Mode:** signature palettes, lookbook saves/deletes, random looks, SVG avatar export.
- **Muse Stories:** branching first-chapter choices and a local story journal.
- **Muse Society:** fictional sample characters, local visit-request drafts, and an event planner.
- **Dark mode:** switch between light and dark appearances; the preference is remembered in the browser.
- **Save backup:** export your local universe as a JSON file and import it later, including on another device. Importing replaces the current local profile after confirmation.
- Responsive layout for desktop and mobile browsers.
- Local profile persistence through browser `localStorage`.

## Important limitations
This is a **front-end prototype**, not the complete production game. The active profile is saved only in the current browser on the current device until you export a backup. It does not yet include real accounts, cloud saves, multiplayer visits, live chat, shared family permissions, a 3D engine, or a live open world. Society characters are fictional samples; visit requests are saved locally and are not sent to real people.

A secure backend and additional game-engine work will be needed for real online multiplayer, synchronized shared households, and advanced 2D/3D character customization.

## Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. Wait for the deployment to finish. The expected URL is `https://factorydefaulth12.github.io/Maison-Muse/`.

GitHub Pages serves the static prototype; it does not provide the shared database or multiplayer backend.
