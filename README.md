# Block 1 Got Lots Or Not

A one-page mobile web app that checks live carpark availability for HDB carpark **BH1** (BLK 1 THOMSON ROAD, Singapore).

- **GOT LOTS** (green) with the number of available lots, or
- **NO LOTS SIAL. GO PARK AT DUSUN** (red) when there are 0 lots.

Auto-refreshes every 60 seconds (and when you come back to the tab), with a manual Refresh button. "Last checked" uses the API's `timestamp` field.

Data source: `https://sg-ev-chargers.9nhi5b.workers.dev/carpark?c=BH1`

## Run

It's a single static file — open `index.html` in a browser, or host it anywhere (e.g. GitHub Pages: Settings → Pages → deploy from this branch, root folder).
