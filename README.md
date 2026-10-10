# 🎟️ Promo Checker - Discord Promo & Link Validator

A fast Python/Node validation tool designed to check the redemption status and expiration dates of Discord promotion links (Xbox Game Pass promos, YouTube Premium promos).

## ✨ Features
- Multi-threaded asynchronous HTTP checks against `discord.com/api/v9/entitlements/gift-codes`.
- Filters invalid, already-claimed, or expired promotional links.
- Exports valid, unredeemed links to `valid_promos.txt`.
