# Prison 365 public preview v4 — deployment checklist

**Destination:** https://prison365.newphysician.org/ (proposed; NOT live as of preparation).
**Domain:** newphysician.org uses Cloudflare DNS. Cloudflare Wrangler on connected NucBox last reported expired authentication. No automatic DNS, SSL or deployment action succeeded.

1. Renew Cloudflare login in the account that controls newphysician.org.
2. Create or select a Cloudflare Pages project; deploy this directory as static assets.
3. Attach prison365.newphysician.org to the Pages project and verify the record was created.
4. Validate HTTPS, domain resolution, web accessibility and internal routes.
5. Verify sample PDF, all images, responsive layouts, Sudoku interaction, email link and sitemap.
6. Do not put sales, donations, bulk pricing or automatic signup live until permissions, production, refunds and fulfillment are settled.

Five supplemental pages: family-guide.html, institutional-review.html, before-surrender.html, editorial-status.html, privacy.html.
