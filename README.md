# Skool (skool)

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
