# African Queen Braiding — Website

**Live:** https://stevendiolosa07-ship-it.github.io/african-queen/

Single-file build: `index.html` — cinematic intro, interactive hairstyle carousel,
pre-booking chat, Calendly scheduler, luxury footer.

## Go-live checklist

1. **Calendly** — set `CONFIG.CALENDLY_URL` at the top of the `<script>` in `index.html`.
   In that Calendly event, add 3 custom questions in this order: Desired length,
   Ends & texture, Color (the chat profile arrives as answers a1/a2/a3).
2. **Client photos** — drop into `assets/` with these exact names:
   `real_client_box_braids.jpg`, `real_client_knotless.jpg`, `real_client_cornrows.jpg`,
   `real_client_stitch_braids.jpg`, `real_client_weaves.jpg`.
   Missing photos show a branded fallback automatically — never a broken image.
3. **Lead capture (optional)** — set `CONFIG.LEAD_ENDPOINT` to the NewSites
   `/contact-form` URL; completed chat profiles POST there even if the visitor never books.

Built by [NewSites](https://stevendiolosa07-ship-it.github.io/NewSites).
