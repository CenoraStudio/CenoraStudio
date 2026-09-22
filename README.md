# CenoraStudio

AI-native bridal and lingerie matching. Turkish ateliers → global brides.

## Repos

| Repo | Role | Vercel |
| --- | --- | --- |
| [CENORA](https://github.com/CenoraStudio/CENORA) | Product API (FastAPI) | not a static site — keep as API |
| [CenoraStudio](https://github.com/CenoraStudio/CenoraStudio) | Public brand site | target project: `cenorastudio` |
| [CRMschaller](https://github.com/Cerenersen-max/CRMschaller) | Ops / partner CRM | do not deploy |

Parked (do not connect): `demo-repository`, `workflows-starter-template`, `nft-marketplace-`.

## Run locally

Open `index.html` or:

```bash
npx serve .
```

## Deploy

Vercel team: `team_deoZQtMfUQCLBna3QH15MVo7`
Existing project: `cenorastudio` → `cenorastudio.vercel.app`

**Blocker (2026-09-22):** Vercel GitHub App is not installed on the `CenoraStudio` org. Install once:
https://github.com/apps/vercel
Then Settings → Git → connect `CenoraStudio/CenoraStudio` to project `cenorastudio`.

`cenorastudios.com` is not on the Vercel registrar. Keep DNS at the current provider; CNAME the host to the Vercel target after the Git link is live.

Brand core: Midnight Blue `#111830`, Plum Perfect `#4A143B`, ivory.
