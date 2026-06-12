# Pika (pika)

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
