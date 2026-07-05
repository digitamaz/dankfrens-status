# dankfrens-status

Uptime monitor for Dank Frens (mainnet).

- Probes every 5 minutes: backend health, market feed (with mainnet DB marker), frontend, on-chain program.
- Alerts via Telegram on failure.
- No application code or data lives here.

Mainnet references:
- Program: `HTVDGm5rVydzGDyoTfZU2C8u3GL6Px6idsXvnMzyNtrJ`
- Mainnet DB marker: genesis collection `7GJq37Y5yRXU2g7deArKAfdq2Pcs7bwauWfjdFKD7aF6` (do not delete this collection from the DB; the monitor keys off it)
