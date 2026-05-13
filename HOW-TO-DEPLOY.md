# How to Deploy These Pages to peakmindsai.com

## Files in this folder
- `terms.html` → peakmindsai.com/terms
- `privacy.html` → peakmindsai.com/privacy
- `refund.html` → peakmindsai.com/refund
- `pricing.html` → peakmindsai.com/pricing

---

## Fastest Option: Deploy to Vercel (Free, 5 minutes)

1. Create a free account at vercel.com
2. Create a new folder on your computer called `peakminds-site`
3. Put all 4 HTML files inside it
4. Go to vercel.com → "Add New Project" → "Deploy from folder" (drag and drop)
5. Vercel gives you a URL like `peakminds-site.vercel.app`
6. In Vercel project settings → Domains → Add `peakmindsai.com`
7. Vercel will show you DNS records to add in GoDaddy

## GoDaddy DNS Settings
1. Go to GoDaddy → My Products → peakmindsai.com → DNS
2. Add the records Vercel gives you (usually an A record and CNAME)
3. DNS propagates in 10–30 minutes

## Then go back to Paddle and enter:
- Web domain: `peakmindsai.com`
- Pricing page: `https://peakmindsai.com/pricing`
- Terms of service: `https://peakmindsai.com/terms`
- Privacy policy: `https://peakmindsai.com/privacy`
- Refund policy: `https://peakmindsai.com/refund`

---

## Alternative: GoDaddy Website Builder (if you don't want Vercel)

GoDaddy has a basic hosting option:
1. In GoDaddy → go to your hosting panel
2. Upload files via File Manager (cPanel)
3. Rename files:
   - `terms.html` → upload to `/public_html/terms/index.html`
   - `privacy.html` → upload to `/public_html/privacy/index.html`
   - `refund.html` → upload to `/public_html/refund/index.html`
   - `pricing.html` → upload to `/public_html/pricing/index.html`

This makes clean URLs like peakmindsai.com/terms (no .html in the URL).
