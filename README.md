# Natera (natera)

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
