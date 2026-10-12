# Julio's Jewelry Repair — Deployment Package

A standalone, responsive website for Julio's Jewelry Repair. This is a separate site package; it does not modify the existing live website or Ultimate Gun Shop deployment. The visual system borrows the dark editorial layout, gold accents, responsive navigation, service-card grid, prominent calls to action, and mobile-first structure from the Ultimate Gun Shop template, with jewelry-specific copy and imagery.

## Files
- `index.html` — complete static website (HTML/CSS/JS)
- `assets/` — Julio logo and six supplied jewelry photos

## Deploy to Netlify
1. Extract this ZIP.
2. In Netlify, choose **Add new site → Deploy manually**.
3. Drag the extracted `julios-jewelry-repair-deploy` folder (the folder containing `index.html`) into the deploy area.
4. After the preview looks right, connect the custom domain `www.juliosjewelryrepair.com` in **Domain management** and follow Netlify's DNS instructions.

## Deploy to Vercel
1. Create a **new** repository for Julio's site and upload the contents of this folder to its root.
2. Import that new repository in Vercel as a **separate project**.
3. Framework preset: Other; Build command: leave blank; Output directory: `.`.
4. Add the domain only after preview testing, then follow Vercel's DNS instructions.

## Before publishing
- Confirm which phone number should be primary: this page uses **(213) 856-8509** and also displays **(213) 489-5290** as an alternate number based on supplied/listed business data.
- Business hours are intentionally omitted because published listings conflict. Add verified hours after confirming directly with the shop.
- Soldering and laser engraving starting prices are labeled as indicative and must be confirmed for the specific item.
- The inquiry form prepares an email in the visitor's email app. It does not send automatically or upload/store photos. Configure a form backend if you want submissions collected directly on the website.
- Review links open Google search results and Yelp search results, rather than claiming any particular review or rating.
- Test the layout, call links, directions, inquiry flow, and all images on mobile before connecting the live domain.

## Domain safety
This package does not change DNS, deploy to hosting, or replace the existing live site. Publish it to a preview first and switch the domain only when you approve it.
