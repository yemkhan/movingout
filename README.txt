# Muzammil's Move-Out Shop
Static HTML site for listing items with photos and prices.

## Quick start (GitHub Pages)
1. Create a new GitHub repo and upload `index.html` (this file is enough).
2. In repo **Settings → Pages**, choose Deploy from **main** branch (root).
3. Your site will go live at `https://<your-username>.github.io/<repo-name>/`.

## How to edit items
- Open `index.html` and scroll to the `window.PRODUCTS` array.
- For each item, update:
  - `name`, `category`, `originalPrice` (optional), `currentPrice`, `description`
  - `images`: array of 3 URLs (you can keep the Unsplash placeholders or replace with your own image URLs).
  - Set `sold: true` to mark as sold (shows a red SOLD ribbon and disables buttons).

## Change contact buttons
- Top-right buttons link to WhatsApp and call with your number `+918139802492`.
- Edit the `href` values in the header if needed.
