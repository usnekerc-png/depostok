# Raw Project — Depo Stok Uygulaması

Repository-ready web application for Raw Project inventory management.

## Features

- Nida Kule and Shape Club inventory tracked independently
- Product categories grouped on the Stock screen
- Product create/edit
- Optional product image and optional expiry date (SKT)
- Branch-specific critical stock limits
- Branch-specific tracking toggle
- Stock entry / exit / waste / physical count
- Inter-branch transfer
- Movement history and basic analytics
- Admin / manager permissions
- Supabase live database integration
- Raw Project branded splash/login UI
- `Designed by anvecan.com` credit

## Deploy with GitHub + Vercel

1. Create a new GitHub repository.
2. Upload **all files in this folder to the repository root**.
3. In Vercel choose **Add New → Project → Import Git Repository**.
4. Framework preset: **Other**.
5. Build command: leave empty.
6. Output directory: leave empty.
7. Deploy.

The app is a static frontend and connects to the existing Raw Project Supabase project.

## Important

Do not upload only `index.html`. `app.js`, `styles.css`, and `logo.png` must stay beside it in the repository root.
