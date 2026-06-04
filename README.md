# University of California, San Diego (ucsd)

University of California, San Diego (UCSD) is a public research university in La Jolla, California, ranked #36 in the QS World University Rankings 2025. This repository catalogs UCSD's public developer and API footprint as an APIs.json provider profile. Most institutional APIs are operated by ITS and gated behind UCSD Single Sign-On; this profile records what is publicly verifiable without fabricating endpoints.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ucsd/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ucsd-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Research
- United States
- California

## APIs

- **UC San Diego ITS Developer Guide** — campus developer guide and architecture/guidelines entry point. Docs: https://developer.ucsd.edu/
- **UC San Diego Web API Portal** — documented campus Web APIs and REST guidelines; SSO-gated to UCSD developers, not open externally. Docs: https://collab.ucsd.edu/api/api-documentation
- **TritonAI Developer API** — centralized LLM gateway (LiteLLM) for approved UCSD users, API-key authenticated. Docs: https://tritonai.ucsd.edu/developer-apis/index.html
- **UC San Diego Library Digital Collections** — public discovery interface over the DAMS repository (100,000+ objects); no documented public API confirmed. Docs: https://library.ucsd.edu/dc/

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/ucsd-plans-pricing.yml](plans/ucsd-plans-pricing.yml)
- Rate Limits: [rate-limits/ucsd-rate-limits.yml](rate-limits/ucsd-rate-limits.yml)
- FinOps: [finops/ucsd-finops.yml](finops/ucsd-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ucsd.edu/
- Developer Portal: https://developer.ucsd.edu/
- GitHub (UCSD): https://github.com/UCSD
- GitHub (UCSD Library): https://github.com/ucsdlib
- LinkedIn: https://www.linkedin.com/school/uc-san-diego/
- Review: [review.yml](review.yml)

## Notes

- Verification caveat: UCSD's documented Web APIs and TritonAI gateway are gated — they require a UCSD Single Sign-On account or approved API keys and are not open to external developers. No open, self-service, externally documented API was found.
- The Library Digital Collections is publicly browsable, but no formal public REST/IIIF/OAI-PMH API surface was confirmed during review.
- The LinkedIn school page returns HTTP 999 to automated requests (LinkedIn anti-bot); the page exists in a browser.
- All URLs were probed live on 2026-06-03; see review.yml for status codes.

## Maintainers

- Kin Lane — kin@apievangelist.com
