# harmio-cron

Calls Harmio's reminder endpoint every 10 minutes. This repo holds no application code or credentials.

Settings → Secrets and variables → Actions → New repository secret:

- `APP_URL`: https://cv-lolos.app
- `CRON_SECRET`: the same value as `CRON_SECRET` on the Harmio server

Run it once by hand from the Actions tab (Run workflow) to check the setup.
# harmio-cron
