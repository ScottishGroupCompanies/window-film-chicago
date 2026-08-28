# Window Film Chicago

Astro static website for **Window Film Chicago**, serving Chicago and surrounding Illinois suburbs.

## Business details

- Website: https://windowfilmchicago.com
- Phone: (773) 453-2005
- Email: contact@windowfilmchicago.com
- Service area: Chicago plus 19 Illinois suburbs listed on `/cities/`

## Development

```bash
npm install
npm run dev
npm run build
```

The production build is written to `dist/`. The project uses one full Chicago city page plus a lightweight service-area directory rather than creating thin pages for every suburb.

## Content and imagery

- City-specific website content was generated through GLM 5.2 and audited for stale market references.
- Chicago-specific imagery is stored in `generated-images/` and wired into stable public asset paths documented in `IMAGE-WIRING-MAP.json`.
- Manufacturer/product specifications and reusable brand assets remain shared.
- Customer names, unsupported star ratings, and unverified project counts have been removed or generalized.

## Deployment

The site is deployed as its own Vercel project. Do not link or deploy this repository into the Salt Lake City Vercel project.

The original `ScottishGroupCompanies/wfp-redesign` repository is read-only and must never be modified.
