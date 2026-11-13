# DukaanLite POS — Offline-First Kirana & Retail Billing PWA

A zero-lag, zero-backend-cost Progressive Web App (PWA) designed for budget Android smartphones to replace expensive billing machines.

## Features
- **10 Indian Languages:** English, Hindi, Tamil, Telugu, Marathi, Bengali, Gujarati, Kannada, Malayalam, Punjabi (instant switch + regional voice recognition).
- **Hardware Camera Barcode Scanner:** Native `BarcodeDetector` API + Web Audio API zero-storage scanner beep + instant new product registration on unknown barcodes.
- **Zero-Storage Voice Search:** Uses Android's built-in Google Speech Engine (`0 KB` bundled model size).
- **Smart POS Billing:** Packet scanning + loose weight quick-taps (`250g`, `500g`, `1kg`, custom grams), toggleable GST (`5%`, `12%`, `18%`), live UPI QR code generation, WhatsApp receipt sharing, and 58mm thermal printing.
- **Stock & Expiry Alerts + Auto Reorder:** Low-stock warnings, 30-day expiry alerts, and 1-tap WhatsApp supplier reorder lists.
- **Udhaar (Credit) Ledger:** Khatabook-style customer credit tracking with WhatsApp payment reminders.
- **100% Offline-First:** IndexedDB storage with persistent storage request (`navigator.storage.persist()`) + JSON backup/restore.

## Deploy Free on GitHub + Render (2 Minutes)
1. Create a new repository on **GitHub** (e.g., `dukaanlite-pos`) and upload all files from this folder (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `render.yaml`, `README.md`).
2. Log in to **Render.com** with GitHub.
3. Click **New +** → **Static Site** → select your `dukaanlite-pos` repository.
4. Set:
   - **Build Command:** *(leave completely blank)*
   - **Publish Directory:** `.`
5. Click **Create Static Site**. Render gives you a free HTTPS URL (required for camera barcode scanning & PWA installation).
6. Open the Render URL in Chrome on the shopkeeper's phone and tap **"Add to Home Screen"** / **"Install App"**.
