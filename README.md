# API Snap (api-snap)

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
