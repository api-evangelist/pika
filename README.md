# Pika (pika)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Pika is an AI-powered video generation platform that allows users and developers to create, edit, and transform video content using natural language prompts, images, and existing video clips. The platform employs advanced diffusion models to produce short-form videos with realistic motion, smooth camera transitions, and detailed scene composition. Developer API access is provided through a partnership with fal.ai, enabling programmatic integration of Pika's 2.2 video models into applications and workflows.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/pika/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pika/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=pika-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=pika-api-evangelist&utm_content=repo)

## Tags

- AI
- Video Generation
- Text-to-Video
- Image-to-Video
- Diffusion Models
- Generative AI
- Media
- Creative Tools

## APIs

### Pika Video API

RESTful API for programmatic AI video generation powered by Pika 2.2 models via fal.ai. Supports text-to-video, image-to-video, Pikascenes, and Pikaframes with configurable resolution (720p/1080p), aspect ratios, and durations of 5-10 seconds. Authentication uses API key via the FAL_KEY environment variable.

- **Documentation:** [https://fal.ai/models/fal-ai/pika/v2.2/text-to-video](https://fal.ai/models/fal-ai/pika/v2.2/text-to-video)
- **API Reference:** [https://fal.ai/models/fal-ai/pika/v2.2/text-to-video/api](https://fal.ai/models/fal-ai/pika/v2.2/text-to-video/api)
- **Human URL:** [https://pika.art/api](https://pika.art/api)
- **Base URL:** https://fal.run/fal-ai/pika

## Plans, Rate Limits, and FinOps

- **Plans & Pricing:** [plans/pika-plans-pricing.yml](plans/pika-plans-pricing.yml)
- **Rate Limits:** [rate-limits/pika-rate-limits.yml](rate-limits/pika-rate-limits.yml)
- **FinOps:** [finops/pika-finops.yml](finops/pika-finops.yml)

### Pricing Summary

| Plan | Price | Credits/Month |
|------|-------|---------------|
| Free | $0/mo | 80 credits |
| Standard | $8/mo (annual) | 700 credits |
| Pro | $28/mo (annual) | 2,300 credits |
| Fancy | $76/mo (annual) | 6,000 credits |
| API (fal.ai) | $0.20/video (720p), $0.45/video (1080p) | Pay-per-use |

### Rate Limits

- 20 video generations per minute (all API users)
- HTTP 429 returned when limit exceeded
- Async queue-based processing with optional webhook callbacks

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://pika.art](https://pika.art) |
| Documentation | [https://fal.ai/models/fal-ai/pika/v2.2/text-to-video](https://fal.ai/models/fal-ai/pika/v2.2/text-to-video) |
| GitHub Organization | [https://github.com/Pika-Labs](https://github.com/Pika-Labs) |
| Blog | [https://pika.art/blog](https://pika.art/blog) |
| Pricing | [https://pika.art/pricing](https://pika.art/pricing) |
| LinkedIn | [https://www.linkedin.com/company/pika-labs](https://www.linkedin.com/company/pika-labs) |
| X | [https://x.com/pika_labs](https://x.com/pika_labs) |

## Maintainers

- **Kin Lane** - [kin@apievangelist.com](mailto:kin@apievangelist.com)
