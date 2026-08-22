# Benchling (benchling-lims)

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

Benchling is a life-sciences R&D cloud - a unified LIMS, electronic lab notebook (ELN), molecular biology registry, sample inventory, and workflow platform for biotech and pharma. Its tenant-scoped REST API (v2) exposes the same objects scientists work with in the UI - DNA/RNA/protein sequences, custom entities and the registry, inventory (boxes, locations, containers, plates), notebook entries, assay results and runs, lab-automation transforms, workflow tasks, and requests - plus events and webhooks for event-driven automation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/benchling-lims/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/benchling-lims/refs/heads/main/apis.yml)

## Tags

- Life Sciences
- Biotech
- LIMS
- Electronic Lab Notebook
- Registry
- Molecular Biology
- Inventory Management
- Assay Management
- Workflows
- Webhooks
- REST

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## APIs

### Benchling AA Sequences API

Amino-acid (protein) sequences.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- AA Sequences

#### Properties

- [OpenAPI](openapi/benchling-lims-aa-sequences-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-aa-sequences-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-aa-sequences-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Apps API

Benchling Apps, app config, canvases, and sessions.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Apps

#### Properties

- [OpenAPI](openapi/benchling-lims-apps-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-apps-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-apps-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Assay Results API

Structured assay results, including transactional bulk loads.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Assay Results

#### Properties

- [OpenAPI](openapi/benchling-lims-assay-results-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-assay-results-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-assay-results-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Assay Runs API

Assay runs and their automation input/output generators.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Assay Runs

#### Properties

- [OpenAPI](openapi/benchling-lims-assay-runs-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-assay-runs-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-assay-runs-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Blobs & Files API

Binary attachments and file objects.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Blobs & Files

#### Properties

- [OpenAPI](openapi/benchling-lims-blobs-files-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-blobs-files-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-blobs-files-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Custom Entities API

Schema-driven custom entities registered in Benchling.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Custom Entities

#### Properties

- [OpenAPI](openapi/benchling-lims-custom-entities-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-custom-entities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-custom-entities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling DNA Sequences API

DNA sequences and sequence-aware operations.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- DNA Sequences

#### Properties

- [OpenAPI](openapi/benchling-lims-dna-sequences-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-dna-sequences-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-dna-sequences-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Entries API

Electronic lab notebook (ELN) entries and templates.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Entries

#### Properties

- [OpenAPI](openapi/benchling-lims-entries-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-entries-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-entries-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Events API

Tenant event stream (also delivered via EventBridge and webhooks).

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Events

#### Properties

- [OpenAPI](openapi/benchling-lims-events-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-events-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-events-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Inventory API

Locations, boxes, containers, and plates for physical samples.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Inventory

#### Properties

- [OpenAPI](openapi/benchling-lims-inventory-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-inventory-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-inventory-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Lab Automation API

Automation input generators and output processors for instrument files.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Lab Automation

#### Properties

- [OpenAPI](openapi/benchling-lims-lab-automation-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-lab-automation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-lab-automation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Molecules API

Small molecules.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Molecules

#### Properties

- [OpenAPI](openapi/benchling-lims-molecules-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-molecules-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-molecules-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Oligos API

DNA/RNA oligos.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Oligos

#### Properties

- [OpenAPI](openapi/benchling-lims-oligos-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-oligos-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-oligos-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Projects & Folders API

Organize entries and entities into projects and folders.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Projects & Folders

#### Properties

- [OpenAPI](openapi/benchling-lims-projects-folders-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-projects-folders-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-projects-folders-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Registry API

Register/unregister entities and browse registry schemas and dropdowns.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Registry

#### Properties

- [OpenAPI](openapi/benchling-lims-registry-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-registry-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-registry-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Requests API

Cross-team service requests, tasks, and fulfillments.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Requests

#### Properties

- [OpenAPI](openapi/benchling-lims-requests-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-requests-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-requests-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling RNA Sequences API

RNA sequences and sequence-aware operations.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- RNA Sequences

#### Properties

- [OpenAPI](openapi/benchling-lims-rna-sequences-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-rna-sequences-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-rna-sequences-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Teams & Organizations API

The Teams & Organizations API from Benchling — 4 operation(s) for teams & organizations.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Teams & Organizations

#### Properties

- [OpenAPI](openapi/benchling-lims-teams-organizations-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-teams-organizations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-teams-organizations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Users API

The Users API from Benchling — 4 operation(s) for users.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Users

#### Properties

- [OpenAPI](openapi/benchling-lims-users-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-users-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-users-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

### Benchling Workflows API

Workflow task groups, tasks, and outputs.

- **Human URL:** [https://docs.benchling.com/reference](https://docs.benchling.com/reference)
- **Base URL:** `https://{tenant}.benchling.com/api/v2`

#### Tags

- Workflows

#### Properties

- [OpenAPI](openapi/benchling-lims-workflows-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/benchling-lims-workflows-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims-workflows-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/registry)
- [API Reference](https://docs.benchling.com/reference)
- [Postman Collection](collections/benchling-lims.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/benchling-lims.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.benchling.com/docs/sequences)
- [Documentation](https://docs.benchling.com/docs/inventory)
- [Documentation](https://docs.benchling.com/docs/entries)
- [Documentation](https://docs.benchling.com/docs/results)
- [Documentation](https://docs.benchling.com/docs/workflows)
- [Documentation](https://docs.benchling.com/docs/requests)
- [Documentation](https://docs.benchling.com/docs/events-getting-started)
- [Documentation](https://docs.benchling.com/docs/getting-started-benchling-apps)
- [Webhooks](https://docs.benchling.com/docs/getting-started-with-webhooks)
- [Documentation](https://docs.benchling.com/docs/organizations)
- [Documentation](https://docs.benchling.com/docs/blobs)

## Common Properties

- [Agentic Access](agentic-access/benchling-lims-agentic-access.yml)
- [Trust Center](security/benchling-lims-trust-center.yml)
- [Domain Security](security/benchling-lims-domain-security.yml)
- [Authentication](authentication/benchling-lims-authentication.yml)
- [O Auth Scopes](scopes/benchling-lims-scopes.yml)
- [GitHub Organization](https://github.com/benchling)
- [LinkedIn](https://www.linkedin.com/company/benchling)
- [Website](https://www.benchling.com)
- [Documentation](https://docs.benchling.com/docs/developer-platform-overview)
- [Plans](plans/benchling-lims-plans-pricing.yml)
- [Rate Limits](rate-limits/benchling-lims-rate-limits.yml)
- [Fin Ops](finops/benchling-lims-finops.yml)
- [Blog](https://www.benchling.com/blog)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
