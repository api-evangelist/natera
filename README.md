# Natera (natera)

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

Natera is a clinical genetic testing company spanning women's health, oncology, and organ health. Rather than a public developer REST API, Natera exposes integration surfaces - Epic Aura bidirectional order/results, OncoEMR (Flatiron) and other EHR connectivity over HL7, the Constellation cloud bioinformatics platform for partner labs, and clinician/patient portals plus a provider mobile app.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/natera/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/natera/refs/heads/main/apis.yml)

## Tags

- Genetic Testing
- Healthcare
- Diagnostics
- EHR Integration
- HL7

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Natera EMR Ordering and Results Integration

Bidirectional electronic ordering and results delivery via the Epic Aura hub and point-to-point HL7, with pre-built orders for all Natera tests in the Epic Foundation System. Not a public REST API; provisioned per health system with an EHR specialist.

- **Human URL:** [https://www.natera.com/emr/](https://www.natera.com/emr/)

#### Tags

- EHR Integration
- Ordering
- Results
- HL7

#### Properties

- [Documentation](https://www.natera.com/emr/)
- [OpenAPI](openapi/natera-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/natera.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/natera.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Natera Epic Aura Hub Integration

Connect once to the Epic Aura (Order and Results Anywhere) hub for secure, HIPAA-compliant bidirectional order and results integration, transmitting order documentation (progress notes, pathology reports, pedigree charts, cancer history) into Natera and results back into the patient EHR.

- **Human URL:** [https://www.natera.com/emr/](https://www.natera.com/emr/)

#### Tags

- Epic
- Aura
- Bidirectional

#### Properties

- [Documentation](https://www.natera.com/emr/)

### Natera OncoEMR (Flatiron) Integration

Natera's oncology testing portfolio integrated into Flatiron Health's cloud-based OncoEMR platform for electronic ordering and results delivery inside the cancer-care clinical workflow.

- **Human URL:** [https://www.natera.com/oncology/](https://www.natera.com/oncology/)

#### Tags

- Oncology
- OncoEMR
- Flatiron

#### Properties

- [Documentation](https://www.natera.com/oncology/)

### Natera Constellation Bioinformatics Platform

Cloud-based platform giving partner laboratories programmatic access to Natera's cell-free DNA bioinformatic algorithms (e.g., Panorama NIPT) to run, monitor, and troubleshoot genetic analysis jobs. B2B partner access, not a public developer API.

- **Human URL:** [https://constellation.natera.com](https://constellation.natera.com)

#### Tags

- Bioinformatics
- cfDNA
- Partner Labs
- NIPT

#### Properties

- [Documentation](https://constellation.natera.com)

### Natera Connect Clinician Portal

Web portal (Women's Health, Oncology, Organ Health, Rare Disease) for clinicians to order kits and supplies, check testing status and results, download and share reports, and schedule genetic counselor conversations.

- **Human URL:** [https://connect.natera.com/users/log_in](https://connect.natera.com/users/log_in)

#### Tags

- Portal
- Clinician
- Ordering

#### Properties

- [Documentation](https://www.natera.com/natera-portal-hub/)

### Natera Provider Mobile App

Provider-facing mobile application backed by Natera's private internal services for managing orders and results on the go. No public API surface is documented for the backend.

- **Human URL:** [https://apps.apple.com/us/app/natera-provider/id1559183134](https://apps.apple.com/us/app/natera-provider/id1559183134)

#### Tags

- Mobile
- Provider
- iOS

#### Properties

- [Documentation](https://apps.apple.com/us/app/natera-provider/id1559183134)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/natera)
- [Website](https://www.natera.com)
- [Documentation](https://www.natera.com/emr/)
- [Plans](plans/natera-plans-pricing.yml)
- [Rate Limits](rate-limits/natera-rate-limits.yml)
- [Fin Ops](finops/natera-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
