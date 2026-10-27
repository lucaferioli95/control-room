# Changelog

All notable changes to the Control Room, newest first. The version number is also shown at the bottom of the app.

## 1.4.1 - 2026-10-27
- Removed the "Notify me" and "Send test" buttons. Setting a reset time now turns on the notification by itself (your phone asks permission the first time), and Clear turns it off.

## 1.4.0 - 2026-10-27
- The Claude usage bar is now a simple "Claude reset" time: pick the time it resets today (no date, no percentage).
- New "Notify me on this device" button: when the reset time arrives, your phone gets a notification, even if the app is closed. Turn it on once per device; "Send test" checks it works.
- Setting a new time re-arms the notification. If the time you pick has already passed today, the app says so instead of saving it.

## 1.3.3 - 2026-10-27
- Small note next to the version showing where the app is hosted (Cloudflare or GitHub Pages), so you can tell the copies apart.

## 1.3.2 - 2026-10-27
- Now also hosted on Cloudflare at its own web address (control-room.luca-ferioli95.workers.dev), so it no longer shares a web address with other apps. Install it fresh from the new address.
- App identity set for the new address.

## 1.3.1 - 2026-10-27
- The "Install app" button is now always visible (unless the app is already installed). If the browser cannot show its own install prompt, it shows short steps for your browser instead. Shared install.js file used by all my apps.

## 1.3.0 - 2026-10-25
- Project details open in a popup (a bottom sheet on phones) instead of pushing the page down. Close with the Close button, Esc, or by tapping outside it.
- New "App" section on each project: paste the app's web address and use "Open app to install" to open it.
- Projects are now shown as a card grid.
- Added this changelog and the version number in the page footer.

## 1.2.0 - 2026-10-25
- Board data now syncs between devices through Supabase and updates live.
- Google sign-in, limited to an allow-list of addresses.
- Starting project list moved out of the code and into the database.

## 1.1.0 - 2026-10-25
- Can be installed as an app (manifest, offline cache, icons) with an Install app button.

## 1.0.0 - 2026-10-24
- First version: project cards with status, summary, next steps, conversation link and topics to discuss.
- Claude usage marker with a countdown to the next reset.
