# API Snap (api-snap)

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

API Snap is a developer utility platform that consolidates 13+ commonly needed REST APIs into a single, unified service with one API key. The platform provides QR code generation, screenshot capture, image resize and conversion, HTML-to-PDF rendering, Markdown-to-HTML conversion, URL metadata extraction, cryptographic hashing, JWT decoding, Base64 encoding/decoding, UUID and unique ID generation, color format conversion, lorem ipsum text generation, and SVG placeholder image generation. API Snap aims to eliminate dependency bloat by letting developers replace small libraries and self-hosted utility services with simple HTTP requests against a managed, rate-limited, multi-tenant API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Utilities
- Developer Tools
- QR Codes
- Screenshots
- Image Processing
- PDF Generation
- Markdown
- URL Metadata
- Hashing
- JWT
- Base64
- UUID
- Color Conversion
- Lorem Ipsum
- Placeholder Images

## Timestamps

- **Created:** 2026-05-06
- **Modified:** 2026-05-19

## APIs

### QR Code API

Generate QR codes encoding any text or URL. Supports configurable size up to 1000 pixels, PNG or SVG output formats, and custom foreground/background hex colors. Returns the encoded image directly with the appropriate content type.

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- QR Codes
- Image Generation
- Encoding

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/qr-generate-example.json)

### Screenshot API

Capture a webpage screenshot by URL. Configurable viewport width and height, output format (PNG or JPEG), and an option to capture the full scrollable page. A managed alternative to running headless Chromium or Puppeteer.

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- Screenshots
- Browser Automation
- Web Capture

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/screenshot-capture-example.json)

### Image Resize API

Resize and convert images. Accepts a binary upload, base64 string, or remote URL. Supports PNG, JPEG, WebP, and AVIF output, configurable quality, target width and height up to 4096 pixels, and standard fit modes (cover, contain, fill, inside, outside).

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- Image Processing
- Image Resize
- Format Conversion

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/resize-image-example.json)

### PDF API

Convert HTML content into a PDF document. Accepts arbitrary HTML and an optional filename title, returning an application/pdf payload with a Content-Disposition header for direct download.

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- PDF
- Document Generation
- HTML to PDF

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/pdf-generate-example.json)

### Markdown API

Convert Markdown content to HTML. Supports a styled mode that returns a full standalone HTML page with default styling, or an unstyled mode that returns a JSON document with the raw HTML fragment for embedding in your own UI.

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- Markdown
- HTML
- Content Conversion

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/markdown-render-example.json)

### URL Metadata API

Extract URL metadata and Open Graph tags for any web page. Returns a structured JSON document with title, description, image, site name, type, favicon, theme color, author, and published date for use in link previews and content cards.

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- URL Metadata
- Open Graph
- Link Preview

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/meta-url-metadata-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/meta-url-metadata-structure.json)
- [Example](examples/meta-extract-example.json)

### Hash API

Compute cryptographic hashes of arbitrary text. Supports MD5, SHA-1, SHA-256, SHA-384, SHA-512, SHA3-256, and SHA3-512 algorithms with hex, base64, or base64url encodings. Available via either GET (query parameters) or POST (JSON body).

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- Hashing
- Cryptography
- Security

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hash-hash-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/hash-hash-result-structure.json)
- [Example](examples/hash-string-example.json)

### JWT Decode API

Decode a JSON Web Token without verification, returning the header and payload as JSON along with computed expiration metadata (expired flag, expiresAt, issuedAt). Useful for debugging tokens and inspecting claims during integration work.

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- JWT
- Tokens
- Security

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/jwt-decode-jwt-decoded-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/jwt-decode-jwt-decoded-structure.json)
- [Example](examples/jwt-decode-example.json)

### Base64 API

Base64 encode or decode an arbitrary string. Supports a URL-safe variant for use in URLs and tokens. Accepts a JSON request body specifying the action and returns the result with a confirmation of the action performed.

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- Base64
- Encoding
- Decoding

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/base64-base64-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/base64-base64-result-structure.json)
- [Example](examples/base64-encode-example.json)

### UUID API

Generate unique identifiers in multiple formats including UUID v4, NanoID, short NanoID, hex, base64, numeric, and timestamp-based IDs. Supports batch generation of up to 100 IDs per request and an optional prefix for typed IDs (e.g. usr_, ord_).

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- UUID
- Identifiers
- ID Generation

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/uuid-id-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/uuid-id-result-structure.json)
- [Example](examples/uuid-generate-example.json)

### Color API

Convert color values between hex, RGB, and HSL formats. Returns structured representations for each format along with computed brightness (0-255) and a derived isDark boolean useful for choosing accessible foreground colors.

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- Color
- Color Conversion
- Design Utilities

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/color-color-conversion-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/color-color-conversion-structure.json)
- [Example](examples/color-convert-example.json)

### Lorem Ipsum API

Generate lorem ipsum placeholder text. Supports configurable paragraph and sentence counts (1-20 each) and either plain text or HTML output for use in design mockups, prototypes, and tests.

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- Lorem Ipsum
- Placeholder Text
- Content Generation

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/lorem-lorem-text-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/lorem-lorem-text-structure.json)
- [Example](examples/lorem-generate-example.json)

### Placeholder Image API

Generate SVG placeholder images for design and prototyping. Supports configurable width and height up to 2000 pixels, custom background and foreground hex colors, and optional custom label text rendered in the center of the image.

- **Human URL:** [https://api-snap.com/](https://api-snap.com/)
- **Base URL:** `https://api-snap.com/api`

#### Tags

- Placeholder Images
- SVG
- Design Utilities

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/api-snap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/api-snap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/placeholder-generate-example.json)

## Common Properties

- [Website](https://api-snap.com/)
- [Documentation](https://api-snap.com/)
- [API Reference](https://api-snap.com/openapi.json)
- [OpenAPI](https://api-snap.com/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Pricing](https://api-snap.com/pricing)
- [Blog](https://api-snap.com/blog)
- [GitHub Organization](https://github.com/apisnap)
- [Authentication](https://api-snap.com/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Plans](plans/api-snap-plans-pricing.yml)
- [Rate Limits](rate-limits/api-snap-rate-limits.yml)
- [Fin Ops](finops/api-snap-finops.yml)
- [JSON-LD](json-ld/api-snap-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/api-snap-spectral-rules.yml)
- [Vocabulary](vocabulary/api-snap-vocabulary.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
