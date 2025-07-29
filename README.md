# Phiri's Heating Solutions — Static Site

This repository is structured for **Cloudflare Pages** (connected to GitHub).

## Deploy to Cloudflare Pages

1. Create a new GitHub repository (e.g., `phiriheating`).  
2. Upload (or push) this folder structure:
   ```
   public/
     index.html
     images/favicon.png
   ```
3. In **Cloudflare** → **Pages** → **Create a project** → **Connect to Git** and select the repo.
4. Build settings:
   - Framework: **None**
   - Build command: *(leave empty)*
   - Build output directory: **public**
5. Complete the wizard. Your site will publish to a `*.pages.dev` URL.
6. Add your custom domain (e.g., `phiriheating.co.uk`) in **Pages → Settings → Custom domains** and follow the DNS steps.

## Notes
- Contact form uses **Formspree** (`action="https://formspree.io/f/maykzxyz"`). Add your final domain to Formspree's allowed domains.
- About section is collapsible and includes **Gas Safe Reg: 918238**.
- Mobile menu and WhatsApp pill in the header are included.
- Replace `public/images/favicon.png` with your own 32x32/64x64 PNG if desired.
