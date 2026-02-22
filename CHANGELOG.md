# 📋 Farm Boy Tracker — Changelog

All notable changes to the app are recorded here, most recent first.

---

## Version 4 — Personalised Labels & Changelog
**Released:** February 2026

### Changed
- "Me" and "My Husband" labels replaced with **Melanie** and **Richard** throughout the app — on the add/edit form and on each product card

### Added
- This changelog
- README documentation file

---

## Version 3 — Shared Sync & Password Protection
**Released:** February 2026

### Added
- **Password protection** — a lock screen is shown when the app is opened; the correct password must be entered to proceed
- **Lock button** (🔒) in the top header — allows manually locking the app at any time
- **Shared product list** — products are now stored in shared cloud storage so both Melanie and Richard see the same list across their devices
- **Auto-sync** — the app checks for updates every 20 seconds and refreshes automatically; a sync status bar shows the current state
- **"Added by" tag** — each product can be tagged as added by Melanie or Richard; this appears as a small label on each product card

---

## Version 2 — Product Search & Barcode Lookup
**Released:** February 2026

### Added
- **Product search** — a search box that queries the Open Food Facts database in real time; selecting a result auto-fills the product name and retrieves a photo of the packaging
- **Barcode lookup** — after a barcode is scanned, the app now attempts to look up the product in the Open Food Facts database automatically; if found, name and photo are filled in
- **Selected product preview** — a confirmation badge shows which product was selected before saving
- Three entry method buttons: **Search**, **Scan Barcode**, **Manual**

### Changed
- Default entry method is now **Search** (previously Manual)
- Photo upload is now optional and secondary to database-retrieved images

---

## Version 1 — Barcode Scanning
**Released:** February 2026

### Added
- **Barcode scanner** — uses the phone's camera to scan product barcodes via Quagga.js
- Camera permission handling with user-friendly status messages
- Barcode confirmation badge shown after a successful scan

### Changed
- Entry method selector added (Manual / Scan Barcode)

---

## Version 0 — Initial Release
**Released:** February 2026

### Added
- Core app structure with green Farm Boy branding
- **Add products** with name, category, star rating (1–5), notes, and photo upload
- **Colour-coded cards** — green border for liked (4–5 stars), red for disliked (1–2 stars), gold for neutral
- **Three tabs** — All, Liked, Disliked
- **Stats bar** — running totals for all, liked, and disliked products
- **Search bar** to filter your tracked products by name, category, or notes
- **Sectioned "All" view** — products grouped into Liked, Mixed/Unrated, and Didn't Like sections
- Local browser storage so products persist between sessions
- Edit and delete functionality on each product card
