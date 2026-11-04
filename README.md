# Family Hub — tablet shell
Static page for a household tablet. It owns the microphone and embeds a private Google Apps Script web app, passing recorded audio to it with `postMessage`.

- No data, accounts or secrets live here. The app URL is entered on the device and kept in its local storage.
- The embedded app accepts messages only from this site's origin and checks the signed-in Google account on every call.
- Published copy of `webapp/tablet-shell` from a private repo. Change it there and republish.
