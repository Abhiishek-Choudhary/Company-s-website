# Company-s-website

Landing page for **Jai Santoshi Casting Company** — a manufacturer of galvanized iron (GI) pipe fittings based on Vidhan Sabha Road, Raipur, Chhattisgarh.

Built with [Astro](https://astro.build/).

## Sections
- **Home** — hero slideshow featuring the Director (Sanjeev Agarwal) and Manager (Krishna Kumar Chaudhary)
- **About** — company story, trust pillars, leadership
- **Products** — full GI fitting range (elbow, tee, socket, union, nipple, reducer, cap, cross) with embedded video guides
- **Contact** — call / email / WhatsApp / Google Maps embed

## Local development

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # static output to ./dist
```

## Deployment

The site is fully static — deploy `dist/` to Netlify, Vercel, Cloudflare Pages, GitHub Pages, or any static host.

## Team photos

Drop portrait JPEGs into `public/`:
- `photo.jpeg` — Manager (Krishna Kumar Chaudhary)
- `public/team/sanjeev-agarwal.jpg` — Director (Sanjeev Agarwal)

If a photo is missing, the site renders a monogram fallback so the layout never breaks.

---

Website made by **Abhishek Choudhary**.
