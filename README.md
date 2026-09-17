# BI Agent Dashboard

Private BI Agent Control Center frontend for the BI Agent project.

## Stack
- Static HTML/JS frontend
- Supabase Auth
- Supabase Edge Function API
- Netlify hosting

## Security
The frontend contains only the public Supabase publishable key. Dashboard data is returned only after authenticated access and an authorization check against the `dashboard_users` allowlist.
