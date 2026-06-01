# Global Kitchen

A simple, single-page WhatsApp order form for **Global Kitchen** — a Ghanaian restaurant.

Customers browse the menu, select items with quantities, optionally share their delivery location (typed address or GPS), and tap **Send on WhatsApp** to place the order directly via WhatsApp Web/App.

## Stack

Pure static HTML, CSS, and vanilla JavaScript — no build step, no dependencies.

## Local development

Just open `index.html` in your browser, or run a tiny local server:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment (Vercel)

1. Push this repo to GitHub.
2. Import the repo on [vercel.com](https://vercel.com/new).
3. Vercel auto-detects the static `index.html` — no build settings or env vars required.
4. Deploy.

## Configuration

A few placeholders to fill in inside `index.html`:

- **Logo** — add a `logo.jpeg` file in this folder (the brand logo from the menu). Until then a 🍽 emoji is shown as a fallback.
- **Business contact card** (top of page): WhatsApp, phone, address, opening hours — search for `[Add ` to find them.
- **Delivery areas** in the location dropdown — search for `[NEEDS_INPUT]`.
- **WhatsApp number** the orders get sent to — search for `WHATSAPP_NUMBER` (currently a placeholder `233000000000`).
