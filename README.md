# LabReserve — Digital Lab Equipment Booking Portal

Static, GitHub Pages-ready academic demo recreation of the LabReserve portal.

## Files
- `index.html` — page markup and views
- `style.css` — responsive UI styling
- `script.js` — front-end demo behavior and browser-local booking storage

## Run locally
Open `index.html` in a browser, or use VS Code Live Server.\n
## Demo login
Any non-empty registration ID and password are accepted.

## Demo behavior / limitations
- Equipment catalogue, search and category filtering work.
- Booking requests can be submitted and are stored in this browser using `localStorage`.
- Dashboard booking counts and booking history update locally.
- There is no server, database, real account authentication, shared booking state, or administrator authorization. Bookings are only visible in the same browser on the same device.

## Publish with GitHub Pages
1. Create a public repository.
2. Upload all three files to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
