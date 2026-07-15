# KwentoKids Funnel — Deploy Package

Files:
- index.html         → the funnel page (loads at your root URL)
- ph-barangays.json  → barangay data, must sit beside index.html
- _headers           → Cloudflare Pages cache rules (auto-detected)

Before going live, replace in index.html:
1. YOUR_PIXEL_ID   → your Meta Pixel ID
2. YOUR_WEBHOOK_URL → your order webhook (Make.com / n8n / Sheets endpoint)
