# API Snap (api-snap)
API Snap is a developer utility platform that consolidates 13+ commonly needed REST APIs into a single, unified service with one API key. The platform provides QR code generation, screenshot capture, image resize and conversion, HTML-to-PDF rendering, Markdown-to-HTML conversion, URL metadata extraction, cryptographic hashing, JWT decoding, Base64 encoding/decoding, UUID and unique ID generation, color format conversion, lorem ipsum text generation, and SVG placeholder image generation. API Snap aims to eliminate dependency bloat by letting developers replace small libraries and self-hosted utility services with simple HTTP requests against a managed, rate-limited, multi-tenant API.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Utilities, Developer Tools, QR Codes, Screenshots, Image Processing, PDF Generation, Markdown, URL Metadata, Hashing, JWT, Base64, UUID, Color Conversion, Lorem Ipsum, Placeholder Images

## Timestamps

- **Created:** 2026-05-06
- **Modified:** 2026-05-06

## APIs

### QR Code API
Generate QR codes encoding any text or URL. Supports configurable size up to 1000 pixels, PNG or SVG output formats, and custom foreground/background hex colors. Returns the encoded image directly with the appropriate content type.

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - QR Codes, Image Generation, Encoding

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [Example](examples/qr-generate-example.json)

### Screenshot API
Capture a webpage screenshot by URL. Configurable viewport width and height, output format (PNG or JPEG), and an option to capture the full scrollable page. A managed alternative to running headless Chromium or Puppeteer.

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - Screenshots, Browser Automation, Web Capture

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [Example](examples/screenshot-capture-example.json)

### Image Resize API
Resize and convert images. Accepts a binary upload, base64 string, or remote URL. Supports PNG, JPEG, WebP, and AVIF output, configurable quality, target width and height up to 4096 pixels, and standard fit modes (cover, contain, fill, inside, outside).

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - Image Processing, Image Resize, Format Conversion

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [Example](examples/resize-image-example.json)

### PDF API
Convert HTML content into a PDF document. Accepts arbitrary HTML and an optional filename title, returning an application/pdf payload with a Content-Disposition header for direct download.

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - PDF, Document Generation, HTML to PDF

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [Example](examples/pdf-generate-example.json)

### Markdown API
Convert Markdown content to HTML. Supports a styled mode that returns a full standalone HTML page with default styling, or an unstyled mode that returns a JSON document with the raw HTML fragment for embedding in your own UI.

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - Markdown, HTML, Content Conversion

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [Example](examples/markdown-render-example.json)

### URL Metadata API
Extract URL metadata and Open Graph tags for any web page. Returns a structured JSON document with title, description, image, site name, type, favicon, theme color, author, and published date for use in link previews and content cards.

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - URL Metadata, Open Graph, Link Preview

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [JSONSchema](json-schema/meta-url-metadata-schema.json)
- [JSONStructure](json-structure/meta-url-metadata-structure.json)
- [Example](examples/meta-extract-example.json)

### Hash API
Compute cryptographic hashes of arbitrary text. Supports MD5, SHA-1, SHA-256, SHA-384, SHA-512, SHA3-256, and SHA3-512 algorithms with hex, base64, or base64url encodings. Available via either GET (query parameters) or POST (JSON body).

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - Hashing, Cryptography, Security

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [JSONSchema](json-schema/hash-hash-result-schema.json)
- [JSONStructure](json-structure/hash-hash-result-structure.json)
- [Example](examples/hash-string-example.json)

### JWT Decode API
Decode a JSON Web Token without verification, returning the header and payload as JSON along with computed expiration metadata (expired flag, expiresAt, issuedAt). Useful for debugging tokens and inspecting claims during integration work.

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - JWT, Tokens, Security

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [JSONSchema](json-schema/jwt-decode-jwt-decoded-schema.json)
- [JSONStructure](json-structure/jwt-decode-jwt-decoded-structure.json)
- [Example](examples/jwt-decode-example.json)

### Base64 API
Base64 encode or decode an arbitrary string. Supports a URL-safe variant for use in URLs and tokens. Accepts a JSON request body specifying the action and returns the result with a confirmation of the action performed.

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - Base64, Encoding, Decoding

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [JSONSchema](json-schema/base64-base64-result-schema.json)
- [JSONStructure](json-structure/base64-base64-result-structure.json)
- [Example](examples/base64-encode-example.json)

### UUID API
Generate unique identifiers in multiple formats including UUID v4, NanoID, short NanoID, hex, base64, numeric, and timestamp-based IDs. Supports batch generation of up to 100 IDs per request and an optional prefix for typed IDs (e.g. usr_, ord_).

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - UUID, Identifiers, ID Generation

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [JSONSchema](json-schema/uuid-id-result-schema.json)
- [JSONStructure](json-structure/uuid-id-result-structure.json)
- [Example](examples/uuid-generate-example.json)

### Color API
Convert color values between hex, RGB, and HSL formats. Returns structured representations for each format along with computed brightness (0-255) and a derived isDark boolean useful for choosing accessible foreground colors.

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - Color, Color Conversion, Design Utilities

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [JSONSchema](json-schema/color-color-conversion-schema.json)
- [JSONStructure](json-structure/color-color-conversion-structure.json)
- [Example](examples/color-convert-example.json)

### Lorem Ipsum API
Generate lorem ipsum placeholder text. Supports configurable paragraph and sentence counts (1-20 each) and either plain text or HTML output for use in design mockups, prototypes, and tests.

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - Lorem Ipsum, Placeholder Text, Content Generation

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [JSONSchema](json-schema/lorem-lorem-text-schema.json)
- [JSONStructure](json-structure/lorem-lorem-text-structure.json)
- [Example](examples/lorem-generate-example.json)

### Placeholder Image API
Generate SVG placeholder images for design and prototyping. Supports configurable width and height up to 2000 pixels, custom background and foreground hex colors, and optional custom label text rendered in the center of the image.

**Human URL:** [https://api-snap.com/](https://api-snap.com/)

**Base URL:** `https://api-snap.com/api`

#### Tags:

 - Placeholder Images, SVG, Design Utilities

#### Properties

- [Documentation](https://api-snap.com/)
- [OpenAPI](openapi/api-snap-openapi.yml)
- [Example](examples/placeholder-generate-example.json)

## Common Properties

- [Website](https://api-snap.com/)
- [Documentation](https://api-snap.com/)
- [APIReference](https://api-snap.com/openapi.json)
- [OpenAPI](https://api-snap.com/openapi.json)
- [Pricing](https://api-snap.com/pricing)
- [Blog](https://api-snap.com/blog)
- [GitHubOrganization](https://github.com/apisnap)
- [Plans](plans/api-snap-plans-pricing.yml)
- [RateLimits](rate-limits/api-snap-rate-limits.yml)
- [FinOps](finops/api-snap-finops.yml)
- [JSONLD](json-ld/api-snap-context.jsonld)
- [SpectralRules](rules/api-snap-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/api-snap.yaml)
- [NaftikoCapability](capabilities/content-generation.yaml)
- [NaftikoCapability](capabilities/developer-utilities.yaml)
- [Vocabulary](vocabulary/api-snap-vocabulary.yaml)

## Authentication

- **bearer** — API key passed via Authorization header (Bearer snp_...) or via the api_key query parameter. Same key works across all 13 endpoints.

## Features

| Name | Description |
|------|-------------|
| Unified API Key | A single Bearer API key (prefix snp_) authorizes all 13+ utility endpoints. No per-service signup or per-product key. |
| REST and JSON | Every endpoint follows a simple REST pattern under https://api-snap.com/api and returns either JSON or the natural binary content type (image, PDF, SVG) for the resource. |
| Predictable Rate Limit Headers | All responses include X-RateLimit-Limit and X-RateLimit-Remaining headers so clients can implement adaptive throttling. |
| GET and POST Variants | Stateless endpoints (hash, qr, uuid, color, meta, lorem, placeholder, screenshot) accept GET with query parameters; mutating endpoints (resize, pdf, markdown, base64, jwt-decode) use POST with a JSON or multipart body. |
| Single REST Service for Many Utilities | Replaces multiple small libraries and self-hosted micro-services for QR generation, screenshots, image resizing, PDF rendering, hashing, and ID generation with one HTTP integration. |
| Format Flexibility | Image and document endpoints accept multiple input formats (binary, base64, URL) and produce multiple output formats (PNG, JPEG, WebP, AVIF, SVG, PDF, HTML). |

## Use Cases

| Name | Description |
|------|-------------|
| Dynamic QR Codes for Marketing | Generate trackable QR codes for campaigns, packaging, business cards, and events without integrating a QR library. |
| Link Preview Cards | Use the URL Metadata API to build rich link previews and bookmark cards in chat apps, CMS platforms, and feed readers. |
| Server-Side Screenshot Automation | Capture webpage thumbnails for SEO, social cards, monitoring dashboards, and visual regression checks without operating headless Chromium. |
| User-Generated Image Resizing | Resize and reformat user uploads on demand for avatars, thumbnails, and responsive images without running an image processing service. |
| HTML-to-PDF Document Generation | Render invoices, receipts, contracts, and reports as PDF directly from HTML templates. |
| ID Generation for Microservices | Centralize UUID, NanoID, and prefixed-ID generation across services without bundling identifier libraries into every codebase. |
| Markdown-Driven CMS Rendering | Convert user or author Markdown into HTML on the fly for blogs, docs sites, and customer-facing UIs. |
| Token Debugging and Inspection | Decode JWTs in admin tooling and developer utilities to inspect claims, issuers, and expiration without writing per-language decoders. |
| Design System and Mockup Tools | Generate placeholder images, lorem text, and color conversions inside design tooling, mockup builders, and component playgrounds. |

## Integrations

| Name | Description |
|------|-------------|
| HTTP Clients | Works with any HTTP client (curl, fetch, axios, requests) via the Authorization Bearer header or api_key query parameter. |
| Headless Browser Replacement | Drop-in replacement for self-hosted Puppeteer or Playwright services handling screenshot and PDF workloads. |
| Image Processing Replacement | Drop-in replacement for libraries such as sharp or imagemagick when consumed as a managed service. |

## Artifacts

Machine-readable API specifications and supporting artifacts organized by format.

### OpenAPI

- [api-snap-openapi.yml](openapi/api-snap-openapi.yml)

### JSON Schema

- [base64-base64-result-schema.json](json-schema/base64-base64-result-schema.json)
- [color-color-conversion-schema.json](json-schema/color-color-conversion-schema.json)
- [hash-hash-result-schema.json](json-schema/hash-hash-result-schema.json)
- [jwt-decode-jwt-decoded-schema.json](json-schema/jwt-decode-jwt-decoded-schema.json)
- [lorem-lorem-text-schema.json](json-schema/lorem-lorem-text-schema.json)
- [meta-url-metadata-schema.json](json-schema/meta-url-metadata-schema.json)
- [uuid-id-result-schema.json](json-schema/uuid-id-result-schema.json)

### JSON Structure

- [base64-base64-result-structure.json](json-structure/base64-base64-result-structure.json)
- [color-color-conversion-structure.json](json-structure/color-color-conversion-structure.json)
- [hash-hash-result-structure.json](json-structure/hash-hash-result-structure.json)
- [jwt-decode-jwt-decoded-structure.json](json-structure/jwt-decode-jwt-decoded-structure.json)
- [lorem-lorem-text-structure.json](json-structure/lorem-lorem-text-structure.json)
- [meta-url-metadata-structure.json](json-structure/meta-url-metadata-structure.json)
- [uuid-id-result-structure.json](json-structure/uuid-id-result-structure.json)

### JSON-LD

- [api-snap-context.jsonld](json-ld/api-snap-context.jsonld)

### Examples

- [base64-encode-example.json](examples/base64-encode-example.json)
- [color-convert-example.json](examples/color-convert-example.json)
- [hash-string-example.json](examples/hash-string-example.json)
- [jwt-decode-example.json](examples/jwt-decode-example.json)
- [lorem-generate-example.json](examples/lorem-generate-example.json)
- [markdown-render-example.json](examples/markdown-render-example.json)
- [meta-extract-example.json](examples/meta-extract-example.json)
- [pdf-generate-example.json](examples/pdf-generate-example.json)
- [placeholder-generate-example.json](examples/placeholder-generate-example.json)
- [qr-generate-example.json](examples/qr-generate-example.json)
- [resize-image-example.json](examples/resize-image-example.json)
- [screenshot-capture-example.json](examples/screenshot-capture-example.json)
- [uuid-generate-example.json](examples/uuid-generate-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [API Snap](capabilities/shared/api-snap.yaml) — 14 operations

### Workflow Capabilities

| Workflow | Description | MCP Tools |
|----------|-------------|-----------|
| [API Snap Content Generation](capabilities/content-generation.yaml) | Workflow that combines API Snap's visual and document generation endpoints (QR code, screenshot, image resize, PDF, Markdown, placeholder, URL metadata) for marketing, content management, and docum... | 7 |
| [API Snap Developer Utilities](capabilities/developer-utilities.yaml) | Workflow that combines API Snap's developer-focused utility endpoints (hash, JWT decode, Base64, UUID/ID generation, color conversion, lorem ipsum) into a single REST and MCP surface. Used by backe... | 6 |

## Vocabulary

- [api-snap-vocabulary.yaml](vocabulary/api-snap-vocabulary.yaml) — 13 resources, 2 workflows, 6 domains, 6 personas

## Rules

- [api-snap-spectral-rules.yml](rules/api-snap-spectral-rules.yml) — 37 Spectral rules enforcing API Snap conventions

## Plans and Pricing

- [api-snap-plans-pricing.yml](plans/api-snap-plans-pricing.yml) — 4 plans (API Commons Plans 0.1)

## Rate Limits

- [api-snap-rate-limits.yml](rate-limits/api-snap-rate-limits.yml) — 5 documented limits (API Commons Rate Limits 0.1)

## FinOps

- [api-snap-finops.yml](finops/api-snap-finops.yml) — 4 meters (FinOps Framework 1.0 / FOCUS-aligned)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

