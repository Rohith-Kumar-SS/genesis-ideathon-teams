# Genesis Ideathon Teams

Public, searchable directory of the 232 Genesis Ideathon 2026 teams, served from GitHub Pages and backed by Supabase.

- **Live:** https://rohith-kumar-ss.github.io/genesis-ideathon-teams/
- **Data:** table `public.ideathon_teams` in the Genesis Supabase project. Public read-only (RLS).
- **Edit teams:** open the table in the Supabase Table Editor and change rows; the site reflects changes on refresh.
- **First-time DB setup:** run `supabase_setup.sql` once in the Supabase SQL editor (creates the table, the public-read policy, and seeds all teams). Re-running it re-seeds safely (upsert by `team_id`).

Theme (logo, palette, fonts) matches the Genesis portal.
