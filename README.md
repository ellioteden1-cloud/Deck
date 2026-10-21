# Deck Studio

An installable, mobile-friendly custom card deck app. Built with HTML, CSS and vanilla JavaScript; no build step or third-party libraries.

## Features
- Create cards with a title, description and colour
- Live card preview
- Shuffle the remaining deck
- Deal 1, 2, 3, 5 or all remaining cards
- Deal face-down and tap to reveal
- Return dealt cards to the deck or clear the table
- Local browser storage preserves cards on the same device
- Offline support through a service worker after the first visit
- Responsive phone and desktop layout

## Try it locally
Because service workers require a secure context, use localhost or HTTPS. If you have Python installed, run this in the project folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Install on your phone
Host the contents of this folder on an HTTPS static host (for example, GitHub Pages, Netlify or another static web host). Open the HTTPS URL on your phone:
- **iPhone:** Safari → Share → Add to Home Screen.
- **Android:** Chrome → menu → Install app / Add to Home screen.

## Notes
This is a local-first PWA, not yet a store-published native app. Decks are stored in browser local storage and do not automatically sync between devices. Clearing browser site data may erase saved decks. The app does not currently include photo uploads, multiple named decks, accounts or multiplayer syncing.
