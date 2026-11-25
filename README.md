# StevieAcademics_App

App front end for YIEMN. The Stevie Academics home app for ages 5+.

## Run it
Open `index.html` in any web browser, or host this folder on any static host (GitHub Pages works).
Keep the `images/` folder next to `index.html`.

## What's in it
- Login with email and password through the YIEMN auth server (create an account with a name, email, password and user type: student, parent or educator)
- Server settings (gear icon on the login page) to set the auth server address and port, with a Test connection button and a "Use offline mode (no server)" checkbox. When it is on, the login page shows a list of offline players you can switch between; points, name, icon and color are saved in the browser
- Five worlds: Money & My Future, Food & Opportunity, Healthy Me, My Green Community, Technology & My Future
- Activities that earn LS Points and levels, plus a visual My Garden
- Profile with icon, color and change name
- Lil Stevie waves when tapped and opens the Stevie Academics YouTube channel

## Files
- `index.html`: the whole app (pages, styles and code in one file)
- `images/stevie-body.png`, `images/stevie-arm.png`: Lil Stevie, with the waving arm separate so only the arm moves

## Notes
- Accounts and passwords live on the YIEMN auth server. Points, icon, color and selfie are saved in each visitor's own browser only and do not sync between devices.
- The auth server must allow this app's origin in its `CORS_ALLOWED_ORIGINS` setting.
- Fonts (Fredoka, Caveat) load from Google Fonts.
