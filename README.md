# Unisys (unisys)
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
