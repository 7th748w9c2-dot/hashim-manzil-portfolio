# hashim-manzil-portfolio

Single-page portfolio for Hashim Manzil, Logistics & Supply Chain Specialist in Dubai. It presents his experience, skills and resume for recruiters.

## Stack
Next.js 14 (App Router), React 18, Tailwind CSS 3. No API keys or environment variables.

## Run locally
```bash
npm install
npm run dev
```
Open http://localhost:3000. Build for production with `npm run build`, then `npm start`.

## Customize
- **All text** lives in `data/content.js`: profile, about, experience, skill groups, education.
- **Resume:** replace `public/Hashim_Manzil_Resume.pdf`, keeping the file name.
- **Colors:** edit the CSS variables at the top of `app/globals.css` (light and dark).
- **Sections:** add or remove components in `app/page.jsx`.

## Deploy
Push to GitHub and import the repo in Vercel. No settings needed.
