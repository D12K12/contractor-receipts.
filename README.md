# Contractor Receipt Tracker

A mobile-first, installable Progressive Web App (PWA) for saving receipt photos and tracking business expenses.

## Publish for free using GitHub Pages
1. Sign in to github.com and create a **public** repository named `contractor-receipts` (public code only; receipt data is not uploaded to the repository).
2. Upload `index.html`, `manifest.webmanifest`, `sw.js`, `icon.png`, and `icon-512.png` from this ZIP to the repository root.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and Save.
4. Wait for the Pages URL to appear, typically `https://YOUR-USERNAME.github.io/contractor-receipts/`.
5. Open that URL on your iPhone in **Safari**, tap **Share → Add to Home Screen → Add**.

## Important limitations
- Receipt images and records are stored in browser IndexedDB **only on the device/browser where you save them**. They do not automatically sync between your iPhone and computer.
- Export **Full backup** regularly, and save the downloaded JSON securely to iCloud Drive or another private location. CSV contains data but **not receipt photos**.
- Avoid clearing Safari website data or deleting the Home Screen app before making a backup.
- This starter app does **not** automatically read receipts, track mileage, or determine tax deductibility. Amounts and dates are entered manually.
- The **Mixed business/personal** option counts the entire expense in the dashboard; review and apportion these expenses separately for tax reporting.
- GitHub Pages serves public source code, but receipts saved inside the app stay in local device storage. Do not upload personal receipt images or backups to your public GitHub repository.
