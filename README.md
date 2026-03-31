# Gambling Vertical Explorer

Google Colab notebook for exploring Everflow's iGaming/gambling data across HubSpot, PlanHat, Gong, Admin, Marketplace, and Agencies.

## Open in Colab

Open `gambling_vertical_explorer.ipynb` in [Google Colab](https://colab.research.google.com), then Runtime > Run All.

## Data Sources
- HubSpot: ~600 gambling/iGaming companies + 188 deals
- Gong: 7 iGaming call transcripts with full text
- PlanHat: Customer success records
- Admin: Everflow platform customer data
- Marketplace: 221 gambling offers
- Agencies: 17 agencies with gaming vertical

## Daily Refresh
pg_cron job runs at 2 AM ET (7 AM London) to pre-compute summary stats.
