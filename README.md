# ⛏️ Veinhost

**Servidores de Minecraft con despliegue en 60 segundos.**

Veinhost es un servicio de hosting de servidores Minecraft orientado al mercado peruano, con RAM dedicada, protección DDoS y despliegue automático de modpacks.

## 🚀 Características

- **Despliegue automático** — El servidor se crea automáticamente al completar el pago
- **Modpacks** — Instalación con un click desde Modrinth y Feed The Beast
- **Plugins y Mods** — Catálogo integrado desde Modrinth
- **Subdominios automáticos** — Cada servidor recibe `usuario.veinhost.com` (sin puerto gracias a SRV records)
- **Panel de control** — Basado en Pterodactyl con tema voxel personalizado
- **Protección DDoS** — Incluida en todos los planes
- **Pagos locales** — Yape, transferencia bancaria y Mercado Pago

## 📋 Planes

| Plan | RAM | CPU | Disco | Precio |
|------|-----|-----|-------|--------|
| Tierra | 2 GB | 100% | 30 GB | S/ 25/mes |
| Hierro | 4 GB | 200% | 40 GB | S/ 45/mes |
| Diamante | 8 GB | 400% | 120 GB | S/ 85/mes |
| Netherite | 10 GB | 400% | 150 GB | S/ 150/mes |

## 🛠️ Stack Técnico

- **Panel**: Pterodactyl + Wings (Docker)
- **Billing**: Paymenter (PHP/Laravel)
- **DNS**: Cloudflare (API para SRV records automáticos)
- **Infraestructura**: VPS con Docker, Coolify como orquestador
- **SSO**: Login unificado entre Veinhost y Pterodactyl

## 🔗 Integraciones

- **Modrinth API** — Modpacks, mods y plugins
- **Feed The Beast** — Modpacks
- **CurseForge API** — Modpacks (próximamente)
- **Cloudflare API** — DNS management automático

## 🌐 Enlaces

- **Sitio web**: [veinhost.com](https://veinhost.com)
- **Panel**: [panel.veinhost.com](https://panel.veinhost.com)

## 📄 Licencia

Propietario — © 2026 Veinhost. Todos los derechos reservados.

---

<p align="center">Desplegá tu mundo en 60 segundos ⛏️</p>
