# OpenClaw Project Guide — Mairket Static Template

## Purpose
This is a framework-free static website. It can be opened, edited, previewed and deployed without WordPress, PHP, Node, a build step, or a database.

## File map
- `index.html` — page copy, metadata, JSON-LD schema and semantic structure.
- `assets/css/main.css` — all visual design and responsive styles.
- `assets/js/main.js` — reveal effects, smooth scrolling and static-form submission logic.
- `assets/img/` — local images.
- `robots.txt` — crawler instructions and sitemap declaration.
- `sitemap.xml` — canonical URL list.
- `llms.txt` — concise AI-readable company/service facts.
- `README.md` — launch/configuration instructions.

## Safe editing rules
1. Keep exactly one descriptive H1 on the home page.
2. Preserve visible answer-first copy for important services and common questions.
3. Keep title, meta description, canonical URL, Open Graph data, visible NAP/contact data, JSON-LD, `llms.txt`, `robots.txt`, and `sitemap.xml` synchronized when business details change.
4. Never invent an address, review count, rating, award, certification, office, service area, client metric, or performance claim.
5. If a real Google Business Profile URL, public street address, social profiles or verified review data are supplied, add them consistently to visible content and Organization/ProfessionalService schema.
6. Create location pages only for places the business genuinely serves and give each page unique local value; do not generate doorway pages.
7. Write for people first. AEO/GEO content should answer questions clearly rather than repeat keywords unnaturally.
8. Preserve semantic HTML (`header`, `nav`, `main`, `section`, `article`, `footer`) and meaningful alt text.

## Common OpenClaw tasks
- Update service descriptions and FAQ answers.
- Create new service pages and add them to sitemap/internal links.
- Create legitimate service-area pages from owner-supplied locations.
- Audit title/meta/H1 alignment.
- Expand FAQ content from real sales questions.
- Add case studies with verifiable evidence.
- Update JSON-LD when factual business details change.

## Form integration
`#intake-form` has an empty `data-endpoint` attribute. Add a real form backend endpoint before production. Do not put private API keys in browser JavaScript.


## Design concept
This package is the **Mairket Agency — Human Touch Concept** version. Preserve `assets/css/variant.css` as the design layer unless the user explicitly asks to change concepts.
