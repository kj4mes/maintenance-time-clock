# Maintenance Work Clock

An iPhone-friendly, installable progressive web app (PWA) for tracking individual maintenance work orders. It stores records locally in the browser on the device; there is no account, server, or cloud sync.

## Features
- Start and stop an individual work order with automatic local time stamps.
- One active job at a time; add completed jobs manually when needed.
- Record work order, property, unit, account code, tenant charge, work-done flag, work description, and stock used.
- Daily totals and job count; browse earlier dates.
- Export CSV and print a daily timesheet (choose Save as PDF in the iPhone print/share sheet).
- Offline support after the first successful load through a service worker.

## Deploy
Host the contents of this folder on any HTTPS static host (GitHub Pages works). For GitHub Pages: repository Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

## Install on iPhone
1. Open the published HTTPS site in Safari.
2. Tap Share → Add to Home Screen → Add.
3. Launch Work Clock from the Home Screen. Open it once while online so the offline cache is populated.

## Data and backup
Entries are saved in this browser's local storage on this iPhone. They do not sync to another device and may be erased if Safari website data is cleared. Export CSV regularly. The print view can be saved as PDF.

## Important notes
- The printed page is a clean digital timesheet based on the fields visible on the supplied Michigan Asset Group form; it is not an exact replica of the original PDF layout.
- Verify all time entries before submitting them. The app is a personal timekeeping aid, not an employer-approved payroll system.
