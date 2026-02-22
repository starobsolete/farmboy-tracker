# 🌿 Farm Boy Product Tracker

A personal web app for tracking Farm Boy house brand products — what you loved, what you didn't, and everything in between.

---

## What It Does

- **Search** for products by name using a live food product database (Open Food Facts) — results auto-fill the product name and pull in a photo of the packaging
- **Scan barcodes** using your phone's camera — the app reads the barcode and attempts to look up the product automatically
- **Rate products** with a 1–5 star system, colour-coded green (liked) and red (disliked) for quick visual scanning
- **Add notes** to each product — great for remembering what you thought or whether you'd buy it again
- **Tag who added it** — Melanie or Richard — so you know whose opinion is whose
- **Shared & synced list** — both users see the same products in real time; updates appear within ~20 seconds
- **Search your list** to quickly find any product you've already tracked
- **Filter by Liked / Disliked** using the tabs at the top
- **Password protected** — a password screen keeps the app private

---

## How to Use It

### Adding a Product
1. Tap the **+** button in the top right
2. Choose how you want to add the product:
   - **Search** — type a product name and pick from the results
   - **Scan Barcode** — point your camera at the barcode on the packaging
   - **Manual** — type everything in yourself
3. Select **Melanie** or **Richard** to tag who is adding it
4. Give it a star rating (1–5)
5. Optionally add a photo and/or a note
6. Tap **Save Product**

### Editing or Deleting a Product
- **Tap any product card** to open and edit it
- Tap the **🗑️ bin icon** on a card to delete it

### Locking the App
- Tap the **🔒 icon** in the top right corner to lock the app
- Anyone opening the link will need to enter the password

---

## Hosting

This app is hosted on **GitHub Pages** and can be accessed via your personal GitHub Pages URL. It works in any modern mobile or desktop browser — no app store required.

To use it like an app on your phone:
- **iPhone (Safari):** Open the link → tap Share → "Add to Home Screen"
- **Android (Chrome):** Open the link → tap the 3-dot menu → "Add to Home Screen"

---

## Updating the App

If a new version of `index.html` is available:
1. Download the new file
2. Rename it to `index.html`
3. Go to your GitHub repository
4. Click **Add file → Upload files**
5. Upload the new `index.html` — it will replace the old one
6. The live site updates within 1–2 minutes

Your product data is stored separately and will **not** be affected by updating the app file.

---

## Data & Privacy

- All product ratings and notes are stored in a **shared cloud storage** tied to this app — not inside the HTML file itself
- The GitHub repository contains only the app code — **no personal data is stored there**
- The app is password protected to prevent unwanted access
- The GitHub repository is public (required for free GitHub Pages hosting), but no personal information is contained within it

---

## Product Database

Product search and barcode lookup is powered by **Open Food Facts** (world.openfoodfacts.org), a free, open, community-built food product database. Coverage of Farm Boy house brand products will vary — popular products are likely to be found; newer or more niche items may need to be entered manually.

---

## Built With

- HTML, CSS, JavaScript (single file — no frameworks)
- [Quagga.js](https://github.com/serratus/quaggaJS) — barcode scanning
- [Open Food Facts API](https://world.openfoodfacts.org) — product search and barcode lookup
- [Google Fonts](https://fonts.google.com) — Playfair Display & DM Sans
- GitHub Pages — free hosting
