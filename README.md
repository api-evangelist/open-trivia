# Open Trivia Database (open-trivia)

The Open Trivia Database (OpenTDB) is a free, user-contributed trivia question database operated by Pixeltail Games LLC. It offers a JSON REST API for retrieving thousands of community-verified trivia questions across 24 categories and three difficulty levels, with optional session tokens to prevent duplicate questions. The service is licensed Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0), is free at the point of use, and enforces a single throttling rule: one request per IP every five seconds.

**URL:** [Visit APIs.json URL](https://opentdb.com/api_config.php)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Tags
Trivia, Games And Comics, Quiz, Open Data, Public APIs, Open Source

## Type
- **x-type:** opensource
- **x-tier:** 3
- **x-license:** CC-BY-SA-4.0
- **x-operator:** Pixeltail Games LLC
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Games & Comics

## APIs

### Open Trivia Database API
JSON REST API that returns multiple-choice and true/false trivia questions drawn from a community-curated database of over 5,000 verified questions across 24 categories.

- [Documentation](https://opentdb.com/api_config.php)
- [Contribute Questions](https://opentdb.com/contribute.php)
- [Browse Questions](https://opentdb.com/browse.php)
- [Play Online](https://opentdb.com/game.php)
- [Global Statistics](https://opentdb.com/api_count_global.php)

## OpenAPI
- [openapi/open-trivia-openapi.yml](openapi/open-trivia-openapi.yml) — 5 paths, 10 component schemas, 4 tags

## Naftiko Capabilities
- [capabilities/open-trivia-questions.yaml](capabilities/open-trivia-questions.yaml) — Questions (1 operation)
- [capabilities/open-trivia-categories.yaml](capabilities/open-trivia-categories.yaml) — Categories (2 operations)
- [capabilities/open-trivia-statistics.yaml](capabilities/open-trivia-statistics.yaml) — Statistics (1 operation)
- [capabilities/open-trivia-tokens.yaml](capabilities/open-trivia-tokens.yaml) — Tokens (1 operation)

## JSON Schema
- [open-trivia-question-schema.json](json-schema/open-trivia-question-schema.json)
- [open-trivia-question-response-schema.json](json-schema/open-trivia-question-response-schema.json)
- [open-trivia-category-schema.json](json-schema/open-trivia-category-schema.json)
- [open-trivia-category-list-response-schema.json](json-schema/open-trivia-category-list-response-schema.json)
- [open-trivia-category-question-count-schema.json](json-schema/open-trivia-category-question-count-schema.json)
- [open-trivia-category-count-response-schema.json](json-schema/open-trivia-category-count-response-schema.json)
- [open-trivia-global-counts-schema.json](json-schema/open-trivia-global-counts-schema.json)
- [open-trivia-global-count-response-schema.json](json-schema/open-trivia-global-count-response-schema.json)
- [open-trivia-token-response-schema.json](json-schema/open-trivia-token-response-schema.json)

## JSON Structure
9 JSON Structure files mirroring the JSON Schemas under [json-structure/](json-structure/).

## JSON-LD
- [open-trivia-context.jsonld](json-ld/open-trivia-context.jsonld) — vocabulary mapped to schema.org and the `otdb:` namespace

## Examples
9 schema-aligned example payloads under [examples/](examples/).

## Spectral Rules
- [rules/open-trivia-rules.yml](rules/open-trivia-rules.yml) — 36 rules covering metadata, paths, operations, parameters, responses, schemas, and security

## Rate Limits
- [rate-limits/open-trivia-rate-limits.yml](rate-limits/open-trivia-rate-limits.yml) — 1 limit (per-IP, one request every 5 seconds) and 5 policies

## Vocabulary
- [vocabulary/open-trivia-vocabulary.yml](vocabulary/open-trivia-vocabulary.yml) — 5 resources, 4 actions, 4 workflows, 6 personas

## Community SDKs and Tools
- [Open Trivia DB Wrapper (TypeScript)](https://github.com/Elitezen/open-trivia-db-wrapper)
- [Python Trivia API](https://github.com/MaT1g3R/Python-Trivia-API)
- [OpenTDB4j (Java)](https://github.com/crnvl/OpenTDB4j)
- [opentdb-api (JavaScript)](https://github.com/blobfysh/opentdb-api)
- [MCP Server (pipeworx-io/mcp-trivia)](https://github.com/pipeworx-io/mcp-trivia)
- [Discord Trivia Bot](https://github.com/LakeYS/Discord-Trivia-Bot)
- [OTDB Source Download Script](https://github.com/QuartzWarrior/OTDB-Source)

## License
Questions are licensed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/). See the [Open Trivia Database terms of service](https://opentdb.com/terms.php).

## Support
- [Contact](https://opentdb.com/contact.php)
- [Donate (Ko-fi)](https://ko-fi.com/pixeltailgames)

## APIs.yml
[apis.yml](apis.yml)

## Timestamps
- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## Maintainers
- **Kin Lane** — kin@apievangelist.com
