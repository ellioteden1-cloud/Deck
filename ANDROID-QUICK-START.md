# Deck Studio — Android quick start

## Important
The ZIP is the app's project files, not an APK. Android cannot install the ZIP directly.

## Easiest route: host the app, then install it from Chrome
1. Extract `deck-studio-app.zip` on a computer, or use a file manager that can extract ZIPs.
2. Upload the *contents* of the extracted folder to an HTTPS static website host. The file `index.html` should be at the root of the hosted site.
3. Wait for the host to publish the site and copy its HTTPS address.
4. On your Android phone, open that HTTPS address in Chrome.
5. In Chrome, tap ⋮ and choose **Install app** or **Add to Home screen** (the wording depends on Chrome and the site).
6. Open Deck Studio from the new home-screen icon.

## Test on a computer first
If Python is installed, open a terminal in the extracted folder and run:
`python -m http.server 8000`
Then open `http://localhost:8000`. This local test is not the installable phone version; installation needs HTTPS hosting.

## Features included
Custom title/description/colour cards, preview, shuffle, deal, face-down reveal, return dealt cards, local persistence and basic offline caching after the first hosted visit.

## Current limitations
- No APK is included.
- Decks stay in that browser on that device; they don't sync across devices.
- Clearing site data may remove saved decks.
- Photo uploads, multiple named decks and multiplayer sync aren't implemented yet.
