# Unisys (unisys)

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

Unisys is a global information technology company that provides specialized solutions integrated with leading-edge security. Unisys delivers digital workplace services, cloud and infrastructure services, and enterprise computing solutions including the ClearPath mainframe platform and the Unisys Stealth zero trust security suite. Unisys serves clients across industries including financial services, government, healthcare, and transportation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Security, Zero Trust, Network Security, IT Services, Cybersecurity, Enterprise Technology

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-03

## APIs

### Unisys Stealth EcoAPI
The Unisys Stealth EcoAPI enables security teams and automation platforms to integrate with Unisys Stealth zero trust network segmentation. Using the EcoAPI, teams can programmatically isolate and un-isolate endpoints and users from the Stealth network in response to security events, retrieve Stealth role configurations, and manage dynamic endpoint isolation workflows. The API uses HTTP Basic authentication against a configurable Stealth server endpoint.

**Human URL:** [https://stealthsecurity.unisys.com](https://stealthsecurity.unisys.com)

**Base URL:** https://stealth-server:8448

#### Tags

- Security, Zero Trust, Network Security, Endpoint Isolation, Cybersecurity

#### Properties

- [Documentation](https://stealthsecurity.unisys.com/resources/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/openapi/unisys-stealth-ecoapi-openapi.yaml)
- [SpectralRules](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/rules/unisys-stealth-spectral-rules.yml)
- [NaftikoCapability - Shared](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/capabilities/shared/unisys-stealth-ecoapi.yaml)
- [NaftikoCapability - Zero Trust Security](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/capabilities/zero-trust-security.yaml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/vocabulary/unisys-vocabulary.yaml)
- [JSON-LD Context](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-ld/unisys-context.jsonld)

#### JSON Schemas

- [Stealth Role](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-schema/unisys-stealth-role-schema.json)
- [Isolation Request](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-schema/unisys-isolation-request-schema.json)
- [Unisolation Request](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-schema/unisys-unisolation-request-schema.json)
- [Action Response](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-schema/unisys-action-response-schema.json)

#### Examples

- [Isolate Endpoint](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/examples/unisys-stealth-isolate-endpoint-example.json)
- [Isolate User](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/examples/unisys-stealth-isolate-user-example.json)
- [Get Stealth Roles](https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/examples/unisys-stealth-get-roles-example.json)

## Features

- **Dynamic Endpoint Isolation** — Programmatically isolate compromised endpoints from the Stealth zero trust network in real time
- **Dynamic User Isolation** — Isolate specific users from network access without disrupting other endpoints or users
- **Combined Isolation** — Simultaneously isolate both an endpoint and associated user in a single API call
- **Role-Based Isolation Policies** — Apply specific Stealth isolation role policies during isolation for granular containment
- **Un-Isolation and Restoration** — Restore isolated endpoints and users to normal Stealth network access after incident resolution
- **Stealth Role Retrieval** — Retrieve available Stealth isolation role configurations for policy selection
- **SOAR/SIEM Integration** — Integrate with security orchestration platforms for automated incident response workflows

## Use Cases

- **Incident Response Containment** — Security operations teams isolate compromised endpoints immediately upon alert detection
- **SOAR Automation** — SOAR platforms trigger Stealth isolation automatically based on SIEM threat detection rules
- **Insider Threat Containment** — Isolate specific users when suspicious activity is detected while preserving investigation access
- **Ransomware Containment** — Rapidly isolate infected endpoints to prevent lateral movement and ransomware spread
- **Compliance-Driven Isolation** — Enforce regulatory compliance by isolating non-compliant endpoints from sensitive network segments

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
