# OmniCalc download stats

Written every hour by the **Download stats** workflow (`.github/workflows/stats.yml` on `main`).

- `downloads.json` — public summary: total downloads, by platform, version and file, update checks, daily history.
  Served at https://raw.githubusercontent.com/msanty573/OmniCalc-Downloads/stats/downloads.json
- `state.json` — the workflow's working data. `excluded` holds the publisher's own test downloads, which aren't counted.
