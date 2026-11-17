# SAVVYEX PWA — Free mobile starter

This is an installable, mobile-first Progressive Web App. It is designed to be added to an Android home screen and launched like an app.

## Features
- Greek-language responsive mobile interface
- Dashboard with income, expenses and estimated balance
- Manual income and expense entries
- Subscription list
- Savings goals and progress
- AI assistant demo interface (not connected to a live AI model)
- Local persistence using browser localStorage
- Offline shell caching through a service worker

## Install on Android
1. Publish these files to a public HTTPS static host (GitHub Pages is free).
2. Open the published HTTPS address in Chrome on Android.
3. Open Chrome menu (⋮) and choose **Install app** or **Add to Home screen**.
4. Confirm. SAVVYEX will appear as an app icon and open in standalone mode.

## Free GitHub Pages publishing
1. On your phone, open github.com and create/sign in to a free account.
2. Create a new public repository named `savvyex`.
3. Upload all five project files (`index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `README.md`) to the repository root. GitHub's mobile web upload may be under **Add file → Upload files**.
4. In repository **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. The URL will be `https://YOUR-USERNAME.github.io/savvyex/`.
6. Open that URL in Chrome on Android and install the app.

## Data and safety
- User-entered data is stored only in localStorage on that browser/device. It is not synced to another device and may be lost if browser data is cleared.
- This prototype has no login, server database, bank integration or real AI. The AI screen uses a fixed demo response.
- Sample records are included; delete or reset them in Profile.
- Do not enter bank passwords, card details or sensitive personal information.
- Before a public production launch, add secure authentication, a backend database, backups/export, privacy controls, a real server-side AI service and legal/privacy review.

## Zero-cost note
The code and local testing are free. GitHub Pages has a free static hosting option for public repositories. App store publishing, custom domains, backend services and real AI usage can involve fees.
