# rivld-web

Static marketing, support, privacy policy, and terms of service site for **RIVLD** — the competitive fitness app.

**Live site:** https://jphjuan18.github.io/rivld-web/

Hosted on [GitHub Pages](https://pages.github.com/) from the `main` branch. Push to `main` to deploy.

## Pages

| Page | URL |
|------|-----|
| Home (Support + Marketing) | https://jphjuan18.github.io/rivld-web/ |
| Privacy Policy | https://jphjuan18.github.io/rivld-web/privacy.html |
| Terms of Service | https://jphjuan18.github.io/rivld-web/terms.html |

## Support

- **Email:** stabri@rivldapp.com

## App Store Connect

Use these URLs when submitting RIVLD to the App Store:

| Field | URL |
|-------|-----|
| Support URL | https://jphjuan18.github.io/rivld-web/ |
| Marketing URL | https://jphjuan18.github.io/rivld-web/ |
| Privacy Policy URL | https://jphjuan18.github.io/rivld-web/privacy.html |

## Custom domain (optional)

To serve at `rivldapp.com` instead of GitHub Pages:

1. Add a `CNAME` file containing `rivldapp.com`
2. In [Settings → Pages](https://github.com/Jphjuan18/rivld-web/settings/pages), set custom domain to `rivldapp.com` and enable **Enforce HTTPS**
3. At your domain registrar, remove Squarespace parking records and add:

| Type | Host | Value |
|------|------|-------|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `jphjuan18.github.io` |

After DNS propagates, update App Store Connect URLs to `https://rivldapp.com/` and `https://rivldapp.com/privacy.html`.
