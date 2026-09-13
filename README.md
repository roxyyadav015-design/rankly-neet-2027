# RANKLY NEET 2027
This is the independent RANKLY web-app codebase, separate from Floot.

## Run locally
Node 20+ → `npm install` → copy `.env.example` to `.env.local` → `npm run dev`.

## Database
Create a Supabase project and run `supabase/schema.sql`.

## Important
The schedule is populated from the supplied Rankly NEET 2027 planner. The question tables are intentionally empty: do not populate them with copied coaching questions or fabricated PYQs. Add only verified/licensed/authorized content.

The current UI is a functional schedule/practice shell. A production CBT needs Supabase Auth, server-side attempt APIs, authoritative timing, scoring, AIR/percentile computation, RLS, admin tools and verified question data before taking payments.
