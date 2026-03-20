# KBB ICO OEM Partner Hub

Internal seller reference tool for KBB ICO OEM programs. Each OEM has a dedicated page with tabs for Products & Pricing, Enrollment, One-Sheeters, Program Overview, and Talking Points.

## Live Programs
- Audi
- GM (Buick, Cadillac, Chevrolet, GMC)
- Honda / Acura
- JLR (Jaguar, Land Rover)
- Kia
- Lexus
- Mazda
- Mitsubishi
- Stellantis (Chrysler, Dodge, Jeep, RAM, Alfa Romeo, Fiat)
- Subaru
- Toyota
- Volkswagen

## Deployment
All files in `/public` are static HTML — no build step required.
Vercel serves `index.html` as the homepage automatically.

## Updating
Edit the relevant OEM HTML file, push to main, Vercel redeploys in ~30 seconds.
