# Open Trivia Database (open-trivia)

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

The Open Trivia Database (OpenTDB) is a free, user-contributed trivia question database operated by Pixeltail Games LLC. It offers a JSON REST API for retrieving thousands of community-verified trivia questions across 24 categories and three difficulty levels, with optional session tokens to prevent duplicate questions. The service is licensed Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0), is free at the point of use, and enforces a single throttling rule: one request per IP every five seconds.

**APIs.json:** [https://opentdb.com/api_config.php](https://opentdb.com/api_config.php)

## Tags

- Trivia
- Games And Comics
- Quiz
- Open Data
- Public APIs
- Open Source

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Open Trivia Database API

JSON REST API that returns multiple-choice and true/false trivia questions drawn from a community-curated database of over 5,000 verified questions across 24 categories. Supports filtering by category, difficulty, and question type, optional response encoding (HTML entities, URL legacy, RFC 3986, Base64), and session tokens to prevent duplicate questions within a six-hour window.

- **Human URL:** [https://opentdb.com/api_config.php](https://opentdb.com/api_config.php)
- **Base URL:** `https://opentdb.com`

#### Tags

- Trivia
- Quiz
- Questions
- Games And Comics

#### Properties

- [Documentation](https://opentdb.com/api_config.php)
- [OpenAPI](openapi/open-trivia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/open-trivia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/open-trivia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/open-trivia-question-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/open-trivia-category-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/open-trivia-question-structure.json)
- [JSON-LD](json-ld/open-trivia-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/open-trivia-rules.yml)
- [Rate Limits](rate-limits/open-trivia-rate-limits.yml)
- [Vocabulary](vocabulary/open-trivia-vocabulary.yml)
- [Examples](examples/open-trivia-question-response-example.json)
- [Sign Up](https://opentdb.com/api_config.php)
- [Contribute Questions](https://opentdb.com/contribute.php)
- [Browse Questions](https://opentdb.com/browse.php)
- [Game Link](https://opentdb.com/game.php)
- [Statistics](https://opentdb.com/api_count_global.php)

## Common Properties

- [Website](https://opentdb.com)
- [Documentation](https://opentdb.com/api_config.php)
- [Support](https://opentdb.com/contact.php)
- [Terms of Service](https://opentdb.com/terms.php)
- [License](https://creativecommons.org/licenses/by-sa/4.0/)
- [Donate](https://ko-fi.com/pixeltailgames)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Community Integrations](https://github.com/topics/opentdb)
- [SDK](https://github.com/Elitezen/open-trivia-db-wrapper)
- [SDK](https://github.com/MaT1g3R/Python-Trivia-API)
- [SDK](https://github.com/crnvl/OpenTDB4j)
- [SDK](https://github.com/blobfysh/opentdb-api)
- [Tools](https://github.com/pipeworx-io/mcp-trivia)
- [Tools](https://github.com/LakeYS/Discord-Trivia-Bot)
- [Tools](https://github.com/QuartzWarrior/OTDB-Source)
- [Code Examples](https://github.com/robinheinze/ignite-trivia)
- [Code Examples](https://github.com/computationalcore/react-native-trivia-quiz)
- [Code Examples](https://github.com/supershaneski/vue-quiz-app)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
