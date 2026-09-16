# RentEase — Revised 200-Customer Version

This is a web-only academic/testing prototype using HTML5, Tailwind CSS CDN, Vanilla JavaScript, and Supabase.

## Included
- Executive dashboard
- Room matrix with live status updates
- Customer directory with live search
- Billing ledger and payment modal
- 200 sample customer records
- 200 sample rooms and 200 sample payments
- Supabase helper module
- `assets/data/demo-seed.sql` for loading the sample data

## Supabase setup
1. Create the `rooms`, `tenants`, and `payments` tables using your schema.
2. Open `assets/js/supabase.js`.
3. Replace `YOUR_SUPABASE_PROJECT_URL` and `YOUR_SUPABASE_ANON_OR_PUBLISHABLE_KEY`.
4. Run `assets/data/demo-seed.sql` in Supabase SQL Editor.
5. Enable Realtime for the three tables if live updates are desired.
6. Upload the folder to GitHub and deploy it with Vercel.

Only use the browser-safe anon/publishable key. Never expose a service_role/secret key.
