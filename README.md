# Signs Plus CNC website recreation

A React + Vite frontend recreating the content, structure, sections, navigation and visual direction of the Signs Plus CNC Lovable website shared in chat.

## Start

1. Install Node.js 18 or newer.
2. Run `npm install` in this folder.
3. Run `npm run dev` and open the address shown in the terminal (usually http://localhost:5173).
4. For deployment, run `npm run build` and host the `dist/` output on Netlify or Vercel with an SPA fallback to `/index.html`.

## Included pages

Home, Services, Our Work (filterable gallery), Shop placeholder, About, Contact, and five-stage Quote form.

## Important before launch

- The **quote form is a frontend demo**. It stores submitted details locally in the visitor's browser; no request is sent to the business. Uploaded artwork is NOT stored or transmitted. Connect Supabase, an email notification service, and authenticated storage before accepting real quote requests.
- The contact form does not send email yet. Connect a backend.
- Images are generic illustrative stock photography loaded remotely from Unsplash, **not images from the reference site or verified Signs Plus CNC projects**. Replace them with business photographs and check rights before commercial use.
- Replace all business contact information and verify services, materials, policies, and pricing before publishing.
- The Shop is a placeholder, not a live checkout.
- Portfolio examples are explicitly identified as samples and not actual completed customer work.
- This is a close structural/style recreation based on the publicly viewable reference. Exact pixel matching and original source assets cannot be guaranteed.

## Customize

Change branding and images in `src/main.jsx` and colours, type and layouts in `src/styles.css`.
