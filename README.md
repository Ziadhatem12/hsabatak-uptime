# hsabatak-uptime
Every 5 minutes GitHub Actions checks `https://app.hsabatak.com/health/ready` through Cloudflare.
On success it pings Healthchecks.io (check "hsabatak public site"). If pings stop for 25 minutes, Healthchecks alerts Telegram and email.
