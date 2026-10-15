# MAAN Creative Agency Website

A production-ready single-page website built with **Next.js 15 + React 19 + TypeScript + Tailwind CSS**.

## Included
- Responsive desktop / tablet / mobile layout
- MAAN brand logo and colours
- English / Somali language toggle
- Scroll reveal animations
- Hover / mouse interactions
- About, Approach, Services, Visual Capabilities, Clients and Contact sections
- Email, WhatsApp and phone actions
- SEO metadata for `maancreative.com`

## Run locally
```bash
npm install
npm run dev
```
Then open `http://localhost:3000`.

## Upload to GitHub
1. Create a new GitHub repository (for example `maancreative-website`).
2. Unzip this project.
3. In Terminal, open the project folder and run:
```bash
git init
git add .
git commit -m "Initial MAAN website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/maancreative-website.git
git push -u origin main
```

## Deploy to Vercel
1. Sign in to Vercel.
2. Click **Add New → Project**.
3. Import the GitHub repository.
4. Vercel should detect **Next.js** automatically.
5. Click **Deploy**.
6. Go to **Project Settings → Domains** and add:
   - `maancreative.com`
   - `www.maancreative.com`
7. Use the DNS records shown by Vercel in Namecheap **Advanced DNS**.

## Main contact details currently used
- Email: `info@maancreative.com`
- Phone / WhatsApp: `+252 61 538 1037`
- Location: Mogadishu, Somalia

## Images
The project uses remote editorial-style imagery from Unsplash via normal `<img/background-image>` URLs. You can replace those URLs in `app/page.tsx` with MAAN's own portfolio images later.
