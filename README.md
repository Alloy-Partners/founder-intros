# founder-intros

The founder-facing page where an Alloy Partners portfolio CEO picks the investor intros they want.

This repo is public on purpose and holds **no data**: only the page. Firms, investors and Alloy connections load
from Supabase after the founder logs in by magic link, and row-level security limits each founder to their own
company. The Supabase URL and publishable key in `config.js` are designed to be public; the secret key never
lives here. Data is published from the private `Alloy-Partners/investornetwork` repo.
