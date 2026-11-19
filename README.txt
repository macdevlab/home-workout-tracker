28-Day Home Strength Challenge Tracker

FILES
- index.html: responsive tracker with daily workout ticks, interval timer, check-ins and trend charts.
- manifest.webmanifest, sw.js, icon.svg: PWA files for installing the hosted app and basic offline loading.

QUICK TEST
1. Open index.html in a modern browser. The tracker works as a standalone file for local testing.
2. Data is saved in local storage in that browser on that device.

INSTALL ON YOUR PHONE / USE ACROSS DEVICES
1. Host the contents of this folder on an HTTPS static host (for example, GitHub Pages or Netlify). Keep all four files in the same folder.
2. Open the hosted HTTPS URL on your phone.
3. iPhone: Safari > Share > Add to Home Screen.
   Android: Chrome > menu (three dots) > Install app or Add to Home screen.
4. Open the app from the home-screen icon.

DATA / LIMITATIONS
- Local data does not automatically sync between devices. Export a JSON backup from Settings & data before switching devices or clearing browser data; import the backup on the other device.
- True multi-device sync, accounts, cloud backups, push notifications and native app-store distribution would require a backend or additional development.
- Exercise is general information, not medical advice. Adapt movements to your ability and stop if you experience warning symptoms.
