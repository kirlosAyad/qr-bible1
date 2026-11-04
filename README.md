# رسائل ربنا ليك – QR Bible Messages
1. Supabase: run `supabase/schema.sql`, then `supabase/seed.sql` (SQL Editor).
2. Copy `.env.example` to `.env.local` and fill in the values (service key stays server-only).
3. `npm install && npm run dev`, then deploy on Vercel with the same env vars.
4. IMPORTANT: seed rows are `needs_review` and are not shown. Compare each with st-takla.org, correct the text to match exactly, then set `verification_status='verified'`.
