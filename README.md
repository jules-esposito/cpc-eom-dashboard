# cpc-eom-dashboard

Public hosting shell for the Appellation / CPC end-of-month operations dashboard.

This repository contains **no financial figures**. `index.html` is a login wall.
All data lives in Supabase (project `vkxjggeuicfrmenqdskl`) behind row-level security:
a request reads nothing unless the signed-in email is active in `viewer_allowlist`.
The Supabase URL and publishable key in the page are public by design and read
nothing without an allowlisted session.

Served via GitHub Pages. Source of truth for the app and pipeline is the private
repo `jules-esposito/cpc-eom-reporting` (site/index.html).
