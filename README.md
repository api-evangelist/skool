# Skool (skool)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Skool is an all-in-one community platform that combines discussion communities, online courses, live calls, and gamification in a single product. It was founded by Sam Ovens and became widely known through its partnership with Alex Hormozi.

**Access model — important:** As of this review, Skool does **not** publish an official public or partner developer REST API. This is a deliberate, long-standing product decision favoring simplicity over an extensible integration surface. The only official programmatic capability is a **Zapier integration**, available on the paid **Pro plan only**, enabled with a per-group **API key** obtained from the group's Plugins settings. That key exists solely to link a Skool group to Zapier — it is not a general-purpose developer API, and Skool publishes no base URL, endpoint reference, OpenAPI description, or WebSocket endpoint.

This is an honest **gated stub**: no API surface is modeled (`endpointsModeled: false`) because Skool documents none.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/skool/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/skool/refs/heads/main/apis.yml)

## Tags

- Community
- Courses
- Online Learning
- Membership
- Creator Economy
- No Public API

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## Official Programmatic Surface

### Skool Zapier Integration

Skool's only official programmatic surface — a Zapier-mediated automation integration, **not** a public REST API. Available on the **Pro plan only** (not Hobby), enabled via a per-group API key found under the group's Plugins settings. Refreshing that key breaks all existing Zaps.

- **Human URL:** [https://help.skool.com/article/56-zapier-integration](https://help.skool.com/article/56-zapier-integration)

Capabilities (fixed set):

- **Triggers:** send paid members' names and email addresses to another app (e.g. a CRM); send membership questions and answers to another app.
- **Actions:** invite a member to a group; unlock a course for a member.

## Unofficial Third-Party Tools (Not Endorsed by Skool)

Several unofficial "Skool API" products exist — Apify actors, `docs.skoolapi.com`, reverse-engineered clients, and Chrome extensions — that read and write Skool posts, comments, members, and courses by calling Skool's **undocumented internal endpoints**. None of these are provided, endorsed, or supported by Skool, and they can break without notice. They are noted here for accuracy only and are **not** represented as an official Skool API in this catalog.

## Pricing

Skool uses flat monthly pricing with a 14-day free trial on each tier (about two months free when billed annually):

- **Hobby — $9/month:** unlimited members, courses, videos, live calls; custom URL; 10% transaction fee. No Zapier integration.
- **Pro — $99/month:** everything in Hobby plus a 2.9% transaction fee, multiple admins (up to 30), advanced plugins, detailed analytics, boosted network discovery, and the **Zapier integration** (the official programmatic surface).

See [plans/skool-plans-pricing.yml](plans/skool-plans-pricing.yml).

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/skool)
- [Website](https://www.skool.com)
- [Documentation](https://help.skool.com)
- [Plans](plans/skool-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
