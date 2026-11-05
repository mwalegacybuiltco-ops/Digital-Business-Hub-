# OYO Command Center

A standalone, installable, offline-capable Progressive Web App. LWA, OYO Technologies and Personal records are isolated by workspace. Only calendar events are shown together in the master calendar.

## Install / deploy

Upload all five app files (`index.html`, `app.js`, `sw.js`, `manifest.webmanifest`, `icon.svg`) to a GitHub repository. In Settings > Pages, choose **Deploy from a branch**, branch `main`, folder `/ (root)`. Open the published HTTPS URL and use your browser's **Install app** / **Add to Home Screen** option. Opening `index.html` directly from disk may work for basic editing but does **not** enable the service worker or installability.

## Data and backup

All records are stored locally in the current browser using localStorage, not on a server. Use **Settings > Export Backup** regularly. Restore JSON backups using **Import Backup**. Backups contain personal and business data; keep them secure. Data does not automatically synchronize between devices. Clearing site data or browser storage without a backup can delete records. The app works offline after its first successful load over HTTPS.

## Features

Separate LWA leads, masterclasses, attendees, purchasers, affiliate sources, commissions, content, tasks and metrics; separate OYO Technologies clients, projects, proposals, invoices, payments, maintenance, client outcomes, content, tasks and metrics; personal tasks, goals and notes; master month/week/day calendar with recurring events; goal/actual snapshots and historical comparison; export/import backup.

## Limitations

No cloud sync, payment processing, PDF invoice generation, email sending, third-party calendar integration or external lead registration integrations. Invoices and payments are records you enter manually. This is a personal local-data tool, not accounting software.
