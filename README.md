# Anna Bieliaha — Winnipeg Real Estate

Premium responsive real estate website, built using Vite and vanilla HTML/CSS/JS with a Vercel serverless contact function.

## Development

```bash
npm install
npm run dev
npm run build
```

## Vercel

Import `appsroket/ana` into Vercel. Framework: **Vite**. Build command: `npm run build`. Output directory: `dist`. Root: `./`.

Set the following environment variables in Vercel for the contact form:

- `RESEND_API_KEY`: server-side Resend API key
- `CONTACT_TO_EMAIL`: Anna's verified inbox for incoming leads
- `CONTACT_FROM_EMAIL`: verified sender address in Resend, e.g. `Leads <leads@yourdomain.com>`

The form **intentionally returns 503 until configured** to avoid silently losing inquiries. Phone and SMS links are fully functional without setup. Once variables are set, redeploy and run a real end-to-end form test.

## Launch checklist

- Confirm Anna approves branding, brokerage relationship, address, languages, and public contact number.
- Replace editorial stock property imagery with licensed brand photography and an approved headshot.
- Verify the review snippets and rating against the current Google listing.
- Connect a custom domain, configure a privacy policy compliant with applicable law, and test forms and mobile UX.
- Add verified property listings or an approved IDX/DDF integration only after arranging data access and required permissions.
- Add analytics only after configuring any required consent handling.

## Notes

Property photographs are illustrative; not actual listings. Ratings reflect provided snapshot and may change. The website does not claim a live IDX search or nonexistent inventory.
