# Luma Atelier B2B

Women’s handbag wholesale site MVP, built as a responsive dependency-free single-page app.

## Run locally

```bash
npm run dev
```

Open the URL shown by Vite. The admin demo is at `#/admin/login` with `admin / admin123`.

## Included

- English / Chinese interface toggle
- Home, collection filtering/search, product pages, about and contact pages
- WhatsApp links and inquiry form
- Admin demo for dashboard, inquiries and product deletion/addition
- Browser local storage for demo products and inquiries

## Production integration

Replace local-storage calls in `src/main.js` with API endpoints backed by Cloudflare D1. Store product image URLs in R2 and send form submissions with Resend. Do not ship the demo credentials in production; authenticate with a hashed password and a secure session cookie.
