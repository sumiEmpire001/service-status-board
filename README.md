# Service Status Board

A responsive service health dashboard using HTML, CSS and vanilla JavaScript. Manually change service states (operational, degraded, outage, maintenance), view overall health, and record incidents in the browser.

## Run

Start `python -m http.server 8000` and open http://localhost:8000.

## Tests

Requires Node.js 18+. Run `npm test` for eight unit tests. GitHub Actions runs tests on pull requests.

## Limitations

This is a **manual demonstration board**, not live uptime monitoring. Statuses and incidents persist only in localStorage. There are no probes, notifications, server synchronization or user permissions. Do not rely on it for production incident management.
