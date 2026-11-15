# Daily Syllabus Deck

A lightweight, single-page study app for reviewing syllabus topics. Browse topics by exam term, mark topics as learned, shuffle the daily topic, and manage the syllabus deck.

## Run locally

Open `index.html` in a modern browser. No build step or package installation is required.

## Deploy with GitHub Pages

The site is static and is ready to publish from the repository root:

1. Push `index.html`, `icon.svg`, and this README to a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch to publish (for example, `main`) and the `/(root)` folder, then save.
5. Open the published URL shown in the Pages settings after deployment completes.

The app and its icon use relative paths, so they work both at a custom domain and at a project URL such as `https://<owner>.github.io/<repository>/`.

## Data and privacy

Topics and progress are stored in the browser's local storage on the device where the app is used. They are not synced between browsers or devices. Google Fonts are loaded from Google Fonts when an internet connection is available; system fonts are used as fallbacks.
