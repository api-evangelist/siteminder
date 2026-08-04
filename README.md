# SiteMinder (siteminder)

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

SiteMinder is an Australian hotel commerce platform (ASX: SDR) connecting more than 53,000 properties with 450+ online distribution channels including OTAs, GDS systems, metasearch sites, and wholesalers. Through its developer portal at developer.siteminder.com, SiteMinder publishes five integration APIs spanning property management system connectivity (pmsXchange), booking channel distribution (SiteConnect, Channels Plus), metasearch publishing (SMX), and direct booking flows (Direct Booking API).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/siteminder/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Hospitality, Hotel Distribution, Channel Manager, Booking Engine, Travel, Property Management, Reservations

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### SiteMinder pmsXchange API
pmsXchange is SiteMinder's integration API for property management systems (PMS), revenue management systems (RMS), and central reservation systems (CRS). Built on OpenTravel Alliance message schemas, it handles two-way exchange of rooms, rates, availability, restrictions, reservations, and payment data between the property's system of record and SiteMinder's channel manager.

**Human URL:** [https://developer.siteminder.com/pmsxchange-api/pmsxchange-api](https://developer.siteminder.com/pmsxchange-api/pmsxchange-api)

#### Tags
- Property Management System, Revenue Management, Central Reservation System, OpenTravel, Reservations, Inventory Distribution

#### Properties
- [Documentation](https://developer.siteminder.com/pmsxchange-api/pmsxchange-api)
- [Quickstart](https://developer.siteminder.com/pmsxchange-api/guides/quick-start)
- [APIReference](https://developer.siteminder.com/pmsxchange-api/guides/api-overview)
- [Certification](https://developer.siteminder.com/pmsxchange-api/guides/testing-and-certification)
- [ChangeLog](https://developer.siteminder.com/pmsxchange-api/additional-resources/changelog)

---

### SiteMinder SiteConnect API
SiteConnect is SiteMinder's booking channel integration API for OTAs, wholesalers, GDS systems, and metasearch partners that contract directly with hotels. It uses OpenTravel Alliance schemas and exposes Rooms and Rates, Availability and Restrictions, Rates, and Reservations resources.

**Human URL:** [https://developer.siteminder.com/siteconnect-api/siteconnect-api](https://developer.siteminder.com/siteconnect-api/siteconnect-api)

#### Tags
- Booking Channel, Channel Manager, OpenTravel, Online Travel Agency, Availability, Rates, Reservations

#### Properties
- [Documentation](https://developer.siteminder.com/siteconnect-api/siteconnect-api)
- [Quickstart](https://developer.siteminder.com/siteconnect-api/guides/quick-start)
- [APIReference](https://developer.siteminder.com/siteconnect-api/guides/api-overview)
- [Certification](https://developer.siteminder.com/siteconnect-api/guides/testing-and-certification)
- [ChangeLog](https://developer.siteminder.com/siteconnect-api/additional-resources/changelog)

---

### SiteMinder Channels Plus API
Channels Plus is SiteMinder's REST and JSON booking channel API that lets partners connect to many SiteMinder properties through a single integration. It exposes property search, real-time shopping, and a full reservation lifecycle alongside a companion MCP server for AI-agent booking flows.

**Human URL:** [https://developer.siteminder.com/channels-plus-api/channels-plus-api](https://developer.siteminder.com/channels-plus-api/channels-plus-api)

#### Tags
- Booking Channel, REST, JSON, Multi-Property, Reservations, Net Rates, Model Context Protocol

#### Properties
- [Documentation](https://developer.siteminder.com/channels-plus-api/channels-plus-api)
- [Quickstart](https://developer.siteminder.com/channels-plus-api/guides/quick-start)
- [APIReference](https://developer.siteminder.com/channels-plus-api/guides/api-overview)
- [MCPServer](https://developer.siteminder.com/channels-plus-api/mcp-server/overview)
- [PartnerPortal](https://developer.siteminder.com/channels-plus-api/additional-resources/commercial/partner-portal)
- [ChangeLog](https://developer.siteminder.com/channels-plus-api/additional-resources/changelog)

---

### SiteMinder SMX API
SMX is SiteMinder's API for metasearch publishers and hotel applications that need a standardized connection to the SiteMinder platform and its network of PMS providers. It provides publisher, hotel, room type, rate plan, availability, and rates resources plus reservation endpoints.

**Human URL:** [https://developer.siteminder.com/smx-api/smx-api](https://developer.siteminder.com/smx-api/smx-api)

#### Tags
- Metasearch, Hotel Application, Availability, Rates, Reservations, OpenTravel

#### Properties
- [Documentation](https://developer.siteminder.com/smx-api/smx-api)
- [Quickstart](https://developer.siteminder.com/smx-api/guides/quick-start)
- [APIReference](https://developer.siteminder.com/smx-api/guides/api-overview)
- [Certification](https://developer.siteminder.com/smx-api/guides/testing-and-certification)
- [ChangeLog](https://developer.siteminder.com/smx-api/additional-resources/changelog)

---

### SiteMinder Direct Booking API
The Direct Booking API is a REST and JSON service that lets hotel groups on SiteMinder's Multi-Property platform power custom direct booking flows. It exposes property listings, individual property detail, room types, room rates, and quote generation. Access is gated by per-tenant API keys.

**Human URL:** [https://developer.siteminder.com/direct-booking-api/direct-booking-api](https://developer.siteminder.com/direct-booking-api/direct-booking-api)

#### Tags
- Direct Booking, REST, JSON, Multi-Property, Property Data, Room Rates, Quotes

#### Properties
- [Documentation](https://developer.siteminder.com/direct-booking-api/direct-booking-api)
- [Quickstart](https://developer.siteminder.com/direct-booking-api/guides/quick-start)
- [APIReference](https://developer.siteminder.com/direct-booking-api/guides/api-overview)
- [Authentication](https://developer.siteminder.com/direct-booking-api/additional-resources/generate-api-key)
- [ChangeLog](https://developer.siteminder.com/direct-booking-api/additional-resources/changelog)

---

## Common Properties

- [Portal](https://developer.siteminder.com/)
- [GettingStarted](https://developer.siteminder.com/get-started/get-started)
- [SignUp](https://www.siteminder.com/developer-guide/)
- [Pricing](https://www.siteminder.com/pricing/)
- [Support](https://developer.siteminder.com/integration-support/integration-support)
- [FAQ](https://developer.siteminder.com/get-started/resources/faq)
- [Glossary](https://developer.siteminder.com/get-started/resources/glossary)
- [Blog](https://www.siteminder.com/r/)
- [TermsOfService](https://www.siteminder.com/legal/)
- [PrivacyPolicy](https://www.siteminder.com/legal/)
- [GitHubOrganization](https://github.com/SiteMinder)
- [LinkedIn](https://www.linkedin.com/company/siteminder)
- [Careers](https://www.siteminder.com/careers/)
- [PartnerPrograms](https://www.siteminder.com/partner-programs/)

## Features

- Channel Distribution to 450+ OTAs, GDS, metasearch, and wholesale partners
- PMS, RMS, and CRS Connectivity via pmsXchange
- Multi-Property management for hotel groups
- Direct Booking Engine for branded booking flows
- Metasearch Publishing via SMX
- Net Rates and Wholesale Distribution via Channels Plus
- Model Context Protocol Server for AI agent booking
- Hotel App Store partner marketplace
- Self-service Partner Portal for deals, invoicing, and API keys

## Use Cases

- Hotel Channel Distribution across hundreds of booking channels
- PMS Integration via pmsXchange for two-way reservation sync
- OTA and Wholesaler Connectivity via SiteConnect or Channels Plus
- Direct Booking Site Build for branded hotel-group websites
- Metasearch Publication via SMX
- AI Agent Booking through the Channels Plus MCP server

## Integrations

- Booking.com, Expedia, Airbnb, Agoda (OTAs)
- Google Hotels, Trivago, TripAdvisor (metasearch)
- Mews, Cloudbeds, Oracle Hospitality (OPERA/Suite8), Apaleo (PMS)
- Amadeus, Sabre, Travelport (GDS)

## Solutions

- Independent Hotels
- Hotel Groups and Chains (Multi-Property + Direct Booking API)
- Booking Channel Partners (SiteConnect, Channels Plus)
- PMS, RMS, and CRS Vendors (pmsXchange)
- Hotel Application Providers (SMX)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
