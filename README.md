# EcoTrail 🌿

**A thoughtful travel discovery experience** for nature escapes, coastal places, and heritage destinations. Built with semantic HTML, modern CSS, and vanilla JavaScript.

## Features

- **Destination discovery:** Browse six sample destinations across nature, heritage, and coast categories.
- **Search and filters:** Search place names, locations, categories, and descriptions.
- **Saved places:** Bookmark destinations; saved state persists in `localStorage`.
- **Destination detail dialogs:** Read seasonal suggestions, activity highlights, and responsible-travel tips.
- **Share destinations:** Uses the Web Share API where supported, with a clipboard fallback.
- **Newsletter interaction:** A client-side demo form with validation and clear feedback.
- **Responsive editorial design:** Large photographic hero, responsive destination cards, mobile navigation, and accessible interaction states.
- **No build step:** No framework or package installation required.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in your browser.
3. Recommended for development: run `python -m http.server 8000` in the project folder, then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a repository named `EcoTrail`.
2. Upload `index.html`, `styles.css`, `app.js`, and this README to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/(root)`, and save.
5. Open the published Pages URL when GitHub finishes deployment.

## Project structure

```text
EcoTrail/
├── index.html     # Landing page, discovery, newsletter, and detail dialog
├── styles.css     # Editorial visual system and responsive layouts
├── app.js         # Destination data, filters, saved places, sharing
└── README.md
```

## Customization ideas

- Replace the sample destinations with researched local recommendations.
- Add verified links to official parks, heritage sites, transport, and local guides.
- Connect the newsletter to a real consent-based mailing-list service.
- Add map embeds and source-backed sustainability information.
- Add image credits and alt text for the specific photos you select.

## Important notes

- Destination copy is illustrative and should be verified before using this as a travel guide.
- Images load from Unsplash URLs and require an internet connection. If a photo URL changes, replace it with a licensed image.
- The newsletter is a front-end demonstration only. It does not collect or send email addresses to a server.
- Favorites are stored locally in the current browser and are not synced across devices.

## Portfolio talking points

- Data-driven rendering from a JavaScript array
- Search + category filtering
- Persistent favorites and accessible dialogs
- Progressive enhancement with Web Share / clipboard APIs
- Responsive CSS grid and editorial layout
- Form validation and interaction feedback

## License

MIT — see [LICENSE](LICENSE).
