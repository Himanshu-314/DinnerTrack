# Dinner Tracker

A small single-page app to track daily dinner meals and calculate the monthly bill.

## Features

- Pick any billing start and end date (can cross months)
- Every day in the period is **subscribed** by default
- Tap a day to mark it **skipped**; tap again to undo
- Bill = subscribed days × price per dinner (default ₹100, editable)
- Add multiple people, each with their own period, price and skipped days
- Data is saved in the browser (`localStorage`), no server needed

## Run locally

Open `index.html` in a browser. No build step or dependencies.

## Deploy on GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your app will be live at `https://<your-username>.github.io/dinner-tracker/`.

## Install as an app

Once deployed on GitHub Pages (HTTPS), open the link on your phone:

- **Android (Chrome):** menu → **Install app** / **Add to Home screen**
- **iPhone (Safari):** Share → **Add to Home Screen**
- **Desktop (Chrome/Edge):** click the install icon in the address bar

It then opens like a normal app and works offline.

## Note

Data lives only in the browser on the device you use, so it does not sync between devices.

## License

MIT
