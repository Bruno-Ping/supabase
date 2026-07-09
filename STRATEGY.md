# Strategy — supabase-selfhost

## What this is
Self-hosted Supabase deployment: Docker Compose definitions (base, Caddy, nginx, S3/rustfs variants), env config, and helper/reset scripts that stand up a real Supabase stack (Postgres, Studio, Auth/GoTrue, Storage, Realtime, Kong, PostgREST, Logflare, etc.) on owned infrastructure. Not a product — it's the database/backend infrastructure other projects run against.

## Role in the portfolio
Active infrastructure. The running containers on this machine (`supabase_db_IVDR.LLM`, `supabase_studio_IVDR.LLM`, `supabase_auth_IVDR.LLM`, `supabase_kong_IVDR.LLM`, etc.) are launched from this repo's compose files and are currently backing the **IVDR.LLM** project's local Postgres/auth/storage stack (per the IVDR.LLM memory note: Next.js + Supabase + Claude API). It is the backend Bruno's Supabase-dependent app repos run on, distinct from the `supabase` repo (which is just the upstream source mirror).

## Scoring
Not applicable — infrastructure, not a scored business asset.
