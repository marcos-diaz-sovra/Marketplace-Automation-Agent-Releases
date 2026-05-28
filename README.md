# Marketplace Automation Agent — Public Releases

Public download mirror for **Marketplace Automation Agent**.

The application's source code lives in a private repository. This repository hosts only the release artifacts (`MarketplaceAgent.exe`) so the in-app auto-updater can reach them through the unauthenticated GitHub Releases API.

## Download

Grab the latest `MarketplaceAgent.exe` from the [Releases page](../../releases/latest). No Python or Playwright install is required — Chromium ships inside the binary.

## In-app updates

From **v2.4.2** onward the application checks this repository on launch. When a newer release is available you'll see a dialog with **Update Now**, which streams the new exe into `%TEMP%`, swaps it on disk, and relaunches automatically. You can also pick **View on GitHub** to read the release notes here, or **Later** to dismiss for the session.

## Version history

Release notes for each version live on the [Releases page](../../releases). Click any tag to see what changed.
