# NEXORA Electronics — Public Website

**Tagline:** Trusted Hong Kong Electronics. Sourced for the World.

A premium, trustworthy, conversion-focused global electronics website for NEXORA Electronics—a Hong Kong-based electronics retailer, sourcing company, enterprise procurement provider, and reseller supplier.

## Overview

This public website serves four commercial audiences:
1. **Retail customers** — Browse and purchase consumer electronics
2. **Enterprise buyers** — Request quotes for bulk procurement
3. **Electronics resellers** — Wholesale sourcing and reseller program
4. **Suppliers & partners** — Supplier onboarding and collaboration

## Brand & Design

- **Aesthetic:** Premium dark electronics design
- **Typography:** Inter (headings, body), Monospace (technical IDs)
- **Color Palette:** Deep blacks, graphite grays, electric cyan accents, trust blue, Hong Kong red
- **Philosophy:** Clean, precise, high-trust—not generic dropshipping or decorative

## Public Commercial Boundaries

### What This Website CAN Publish
- Published products & variants
- Approved product images & videos
- Retail prices & legitimate compare-at prices
- B2B price-request eligibility
- High-level availability (In Stock, Limited, Preorder, Sourcing Available)
- Supported shipping regions
- Public warranty terms
- Product condition (New, Certified Refurbished, Grade A/B/C, Open Box, Parts Only)
- Approved specifications & technical details
- Approved customer reviews & ratings
- Approved promotions
- Public tracking status
- Public serial-verification results

### What This Website MUST NEVER Expose
- ❌ Supplier cost, landed cost, gross margin
- ❌ Exact warehouse stock quantities
- ❌ Supplier identity (unless approved)
- ❌ Internal procurement records
- ❌ Customer records belonging to other users
- ❌ Unrestricted serial or IMEI lookup history
- ❌ Internal fraud scores or risk alerts
- ❌ Employee information
- ❌ Audit logs or security events
- ❌ API credentials or environment variables
- ❌ Internal/administrative routes

## Non-Negotiable Standards

✅ **No dead links** — Every visible action works or shows clear unavailable state
✅ **No fake checkout** — Real payment integration or documented sandbox boundary
✅ **No fake availability** — Real inventory data or sourcing eligibility
✅ **No unpublished products** — Direct URL guessing cannot reach unpublished items
✅ **No internal routes exposed** — Public navigation never links to admin/internal systems
✅ **No price simulation** — Prices are real or clearly labeled as estimates
✅ **Secure by default** — Public/private boundary enforced at every layer
✅ **Accessible & responsive** — Keyboard navigation, focus states, mobile-first design
✅ **Production quality** — No placeholder content or half-built features

## Technical Stack (To Be Configured)

- **Frontend Framework:** Next.js (SSR, SEO, performance)
- **Styling:** Tailwind CSS + custom design tokens
- **Database:** PostgreSQL (products, orders, applications, content)
- **Authentication:** JWT sessions, secure account routes
- **Payments:** Shopify/Stripe/Airwallex integration boundary
- **APIs:** GET-OS public catalog & publishing APIs (data boundaries enforced)
- **Search:** Elasticsearch or Algolia (approved public fields only)
- **Analytics:** Privacy-safe event tracking
- **Hosting:** CDN + edge caching

## Sequential Build Prompts

1. ✅ **PROMPT 1** — Public Website Foundation (routes, design, components, security)
2. ⏳ **PROMPT 2** — Premium Homepage (hero, categories, trust signals)
3. ⏳ **PROMPT 3** — Catalog, Collections & Search (discovery, filters, sorting)
4. ⏳ **PROMPT 4** — Product Detail & Conversion (specs, variants, reviews)
5. ⏳ **PROMPT 5** — Cart, Checkout & Order Handoff (payment integration)
6. ⏳ **PROMPT 6** — Enterprise Procurement & Bulk Orders (RFQ, sourcing)
7. ⏳ **PROMPT 7** — Reseller & Supplier Acquisition (applications, intake)
8. ⏳ **PROMPT 8** — Warranty, Returns, Tracking & Verification (after-sales)
9. ⏳ **PROMPT 9** — Trust, Company, Content & Legal (about, policies, support)
10. ⏳ **PROMPT 10** — SEO, Analytics, Performance & Launch Hardening

## Repository Structure

```
nexora-public-website/
├── src/
│   ├── app/                          # Next.js app directory
│   ├── components/                   # Reusable component library
│   │   ├── common/                   # Header, footer, nav
│   │   ├── commerce/                 # Product cards, filters, cart
│   │   ├── forms/                    # RFQ, applications, warranty
│   │   ├── states/                   # Loading, empty, error states
│   │   └── ui/                       # Buttons, cards, modals, drawers
│   ├── lib/                          # Utilities & helpers
│   │   ├── routes.ts                 # Route registry
│   │   ├── design-tokens.ts          # Colors, typography
│   │   ├── data-contracts.ts         # Public API schemas
│   │   ├── security.ts               # Auth, CSRF, rate limiting
│   │   └── validation.ts             # Input validation
│   ├── pages/                        # Route handlers
│   ├── styles/                       # Global styles
│   └── types/                        # TypeScript interfaces
├── public/                           # Static assets
├── tests/                            # Tests
├── docs/                             # Documentation
│   ├── ROUTES.md                     # Route manifest
│   ├── COMPONENTS.md                 # Component library
│   ├── DATA-CONTRACTS.md             # API boundaries
│   └── SECURITY.md                   # Security architecture
├── .env.example                      # Environment template
└── package.json                      # Dependencies
```

## Getting Started

```bash
npm install
cp .env.example .env.local
npm run dev
```

---

**NEXORA Electronics** — Trusted Hong Kong Electronics. Sourced for the World.
