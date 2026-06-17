# Veinhost

Instant Minecraft server hosting for the Peruvian market. Deploy in 60 seconds with dedicated RAM, DDoS protection, and automatic modpack installation.

## Features

- **Auto-deployment** — Server provisions automatically after payment
- **One-click modpacks** — Install from Modrinth and Feed The Beast
- **Plugins & mods** — Browse and install directly from the panel
- **Free subdomains** — Every server gets `yourname.veinhost.com` with automatic SRV records (no port needed)
- **DDoS protection** — Included on all plans at no extra cost
- **Local payments** — Yape, bank transfer, and Mercado Pago

## Plans

| Plan | RAM | CPU | Storage | Price (PEN) |
|------|-----|-----|---------|-------------|
| Tierra | 2 GB | 1 vCPU | 30 GB SSD | S/ 25/mo |
| Hierro | 4 GB | 2 vCPU | 40 GB SSD | S/ 45/mo |
| Diamante | 8 GB | 4 vCPU | 120 GB SSD | S/ 85/mo |
| Netherite | 10 GB | 4 vCPU | 150 GB SSD | S/ 150/mo |

## Tech Stack

- **Game Panel**: Pterodactyl + Wings (Docker)
- **Billing**: Paymenter (Laravel)
- **DNS**: Cloudflare API (automatic SRV record creation)
- **Infrastructure**: Docker containers on Ubuntu VPS

## Integrations

- **Modrinth API** — Modpacks, mods, and plugin catalog
- **Feed The Beast** — Modpack distribution
- **Cloudflare API** — Programmatic DNS management for subdomains and SRV records

## Links

- **Website**: [veinhost.com](https://veinhost.com)
- **Game Panel**: [panel.veinhost.com](https://panel.veinhost.com)

## License

© 2026 Veinhost. All rights reserved.
