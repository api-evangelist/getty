# Getty Images (getty)

Getty Images is a premium stock media licensor of editorial and creative photography, illustrations, video, and music. The Getty Images API exposes search, asset metadata, and download endpoints for licensing partners and enterprise customers. Authentication is via API key + OAuth 2.0 client credentials.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/getty/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- Stock Media, Images, Editorial, Video, Music, Licensing

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Getty Images API
REST API at /v3 covering creative and editorial image search, video search, asset detail retrieval, and download endpoints with size/license selection. All requests require an api-key header; elevated operations (downloads, account-scoped) require an OAuth 2.0 bearer token via client credentials grant.
- **Base URL:** `https://api.gettyimages.com/v3`
- **Docs:** https://developer.gettyimages.com/docs/

## Common Properties
- [Website](https://www.gettyimages.com/)
- [Developer Portal](https://developer.gettyimages.com/)
- [OpenAPI](https://api.gettyimages.com/swagger)
- [Plans](plans/getty-plans-pricing.yml) — reconciled (sales-led licensing agreement)
- [RateLimits](rate-limits/getty-rate-limits.yml) — reconciled (per-key QPS; contract-defined)
- [FinOps](finops/getty-finops.yml) — reconciled (subscription + per-asset entitlement)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
