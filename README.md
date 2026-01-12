[![Deploy with Dokploy](https://img.shields.io/badge/Deploy_with-Dokploy-black)](https://dealenx.github.io/Dokployfile/dealenx/dokployfile-wg-easy)

# WG-Easy for Dokploy

WG-Easy is a simple and user-friendly WireGuard VPN server with a web interface for easy management.

## Prerequisites

- 🌐 **Domain name** — you need a domain pointed to your server (e.g., `vpn.example.com`)
- 🔐 **HTTPS/SSL** — configure Traefik in Dokploy or bind your domain and enable SSL manually

## Access

The web interface runs on port `51821`. Depending on your setup, you can access it in different ways:

**Via Traefik proxy (standard port 80/443):**

```
http://vpn.example.com
https://vpn.example.com
```

**Directly via port 51821:**

```
http://<your-domain>:51821
```

For example with Traefik wildcard domain:

```
http://utils-wireguard-3vtbal-874f65-155-212-184-136.traefik.me:51821
```

## Features

- 🔒 Secure WireGuard VPN
- 🌐 Web-based management interface
- 📱 Easy client configuration with QR codes
- 🚀 One-click deployment with Dokploy

## Links

- [GitHub](https://github.com/wg-easy/wg-easy)
- [Website](https://wg-easy.github.io/)
- [Documentation](https://github.com/wg-easy/wg-easy/wiki)
