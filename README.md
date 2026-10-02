## DESIGN CONCEPT

Mairket Agency — Human Touch Concept

A human, hand-drawn agency website concept optimized for SEO, AEO, GEO and local search.

# Mairket — Static Agency Template

This version removes WordPress completely. It is plain HTML, CSS and JavaScript and can be uploaded to a normal static host or used directly in an OpenClaw workspace.

## Preview
Open `index.html` in a browser. For best local testing, serve the folder with any simple HTTP server.

## Before launch
1. Confirm the canonical production domain. Current template uses `https://mairket.com/`.
2. Confirm public business name, phone, email and hours.
3. Supply the exact verified Google Business Profile URL and public address only if applicable; then update visible content + JSON-LD + `llms.txt` consistently.
4. Connect the intake form by setting `data-endpoint="YOUR_FORM_ENDPOINT"` on `<form id="intake-form">`. The included JavaScript submits standard FormData and expects an HTTP success response.
5. Add analytics/consent tooling only after the account IDs and privacy requirements are known.
6. Replace or optimize images as needed and keep descriptive alt text.
7. Submit `https://mairket.com/sitemap.xml` in Google Search Console after deployment.

## Search optimization included
- Search-focused title and description
- Canonical URL and crawl directives
- Open Graph / Twitter metadata
- Semantic headings and landmarks
- Answer-first company summary
- Service-specific semantic copy
- Miami/local relevance section
- FAQ content and FAQPage schema
- Organization/ProfessionalService/WebSite/WebPage/ItemList structured data
- `robots.txt`
- `sitemap.xml`
- expanded `llms.txt`
- OpenClaw editing guardrails

## Important GBP note
The template intentionally does not invent a street address, rating, review count or GBP URL. Add only verified real-world business information.
