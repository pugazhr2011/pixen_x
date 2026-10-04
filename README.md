# 🔥 Pixen Store

Fire-themed e-commerce web app (static, runs in any browser / mobile).

## Structure
- `index.html` – page shell
- `css/style.css` – styles
- `js/app.js` – app logic (login, store, cart, checkout, admin panel)

## Features
- Mandatory login (Gmail / username / mobile + OTP) before home page
- Home banner controlled by Admin (image, notice text, link)
- Admin Panel: Orders, Products (Edit / Delete), Offers (1–100% codes, 1000-code generator), Site (banner + support Gmail)
- Admin-only Edit / Delete Product buttons at bottom of product details
- Checkout validation (10-digit mobile, state, district, 6-digit PIN)

## Admin login
Mobile `8807064016` (change `ADMIN_PH` / `ADMIN_MAIL` at top of `js/app.js`).

## Run
Open `index.html`, or host free with GitHub Pages:
1. Create a repo, upload all files keeping the folders.
2. Settings → Pages → Branch `main` / root → Save.

## Notes
- OTP is **demo mode** (shown on screen). Real SMS/WhatsApp/Gmail OTP needs a backend (e.g. Twilio).
- Data is stored in the visitor's browser (localStorage), not a shared database.
