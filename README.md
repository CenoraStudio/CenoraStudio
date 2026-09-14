# CenoraStudio

AI-native bridal and lingerie matching. Turkish ateliers → global brides.

## Repos

| Repo | Role |
| --- | --- |
| [CENORA](https://github.com/CenoraStudio/CENORA) | Product API (FastAPI) |
| [CenoraStudio](https://github.com/CenoraStudio/CenoraStudio) | Public brand site |
| [CRMschaller](https://github.com/Cerenersen-max/CRMschaller) | Ops / partner CRM |

## Run locally

Open `index.html` or:

```bash
npx serve .
```

## Deploy

Vercel project should point at this repository, production branch `main`.
Cloudflare DNS stays in front: proxied CNAME to the Vercel target.

Brand core: Midnight Blue `#111830`, Plum Perfect `#4A143B`, ivory.
