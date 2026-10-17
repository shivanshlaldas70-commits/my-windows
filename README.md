# RebootReady — Windows Recovery Preparation

RebootReady is an early-stage concept for helping everyday Windows users prepare for common recovery situations before something goes wrong.

## Try the interactive prototype

Open [RebootReady HTML prototype](prototype/RebootReady_Professional.html) in this repository. It includes a sample device profile, user-controlled readiness checklist, official support links, and a recovery guide.

**Demo boundary:** the HTML prototype uses sample data only. It does not inspect your computer, download or install drivers, repair Windows, or create recovery media.

## What's in this repository

- `prototype/RebootReady_Professional.html` — interactive browser-based concept prototype
- `REBOOTREADY_PROJECT.md` — project overview and concept details
- `LICENSE` — repository license

## Desktop source package status

The separate v0.4.0 WPF/.NET 8 desktop source archive is **not currently included in this repository**. The HTML prototype is separate from that desktop source package.

## Safety and limitations

This is an early prototype, not a production Windows recovery utility. It does not automatically reinstall or repair Windows, restore drivers, or create bootable recovery USB media. Do not rely on it as your only recovery plan. Back up important files to a separate location and verify official Microsoft or laptop-manufacturer instructions before attempting recovery actions.

## Build status

The HTML prototype can be opened in a browser. The separate WPF desktop app has not been compiled or validated on Windows in this environment.
