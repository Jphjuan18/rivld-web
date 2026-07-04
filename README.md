# gymr-web

Marketing, support, privacy policy, and terms of service for [RIVLD](https://rivldapp.com).

## Live URLs

| Page | URL |
|------|-----|
| Home (Support + Marketing) | https://rivldapp.com/ |
| Privacy Policy | https://rivldapp.com/privacy |
| Terms of Service | https://rivldapp.com/terms |

GitHub Pages fallback: https://jphjuan18.github.io/gymr-web/

## Custom domain setup

1. In repo **Settings → Pages**, set custom domain to `rivldapp.com` and enable **Enforce HTTPS**.
2. At your domain registrar, remove Squarespace parking records and add:

| Type | Host | Value |
|------|------|-------|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `jphjuan18.github.io` |

3. Wait for DNS propagation and GitHub's TLS certificate (usually minutes, up to 24h).

## App Store Connect

- **Support URL:** https://rivldapp.com/
- **Marketing URL:** https://rivldapp.com/
- **Privacy Policy URL:** https://rivldapp.com/privacy
