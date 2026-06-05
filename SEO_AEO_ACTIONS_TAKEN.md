# PulseMeasurement SEO and AEO Actions Taken

Last updated: 2026-06-05

This document records the search engine optimisation (SEO), answer engine optimisation (AEO), and performance actions implemented for `https://pulsemeasurement.com`.

## SEO Actions Taken

### Domain and Indexing Foundations

- Confirmed the public website is served from `https://pulsemeasurement.com`.
- Added and deployed `sitemap.xml` at `https://pulsemeasurement.com/sitemap.xml`.
- Added and deployed `robots.txt` at `https://pulsemeasurement.com/robots.txt`.
- Updated the Azure Static Web Apps workflow so `robots.txt`, `sitemap.xml`, and static assets are included in the production deployment artifact.
- Added canonical metadata to the homepage:
  - `https://pulsemeasurement.com/`

### Homepage Metadata

- Rewrote the homepage title to clarify the product category:
  - `PulseMeasurement | Organisational Intelligence Software`
- Rewrote the homepage meta description to define PulseMeasurement as organisational intelligence software for:
  - weekly AI-guided employee conversations
  - people risk detection
  - manager briefings
  - strategy alignment
  - closed-loop action

### Crawl and Deployment Hygiene

- Ensured all new public content pages were included in `sitemap.xml`.
- Verified new pages on the live domain after Azure deployment.
- Preserved stable `.html` URLs for resource and definition pages.
- Added a deployable logo asset at:
  - `https://pulsemeasurement.com/assets/logo.svg`

### Performance Improvements

- Removed broad `transition: all` rules from interactive UI elements flagged by diagnostics.
- Replaced unnecessary animation of colour and border changes with immediate state changes.
- Kept compositor-friendly transitions only where useful, such as `transform` and `box-shadow`.
- Deferred below-the-fold interactive initialization for:
  - the PM3 architecture UI in the `#technology` section
  - the 12-pillar value proposition UI in the `#value-proposition` section
- Added idle and visibility-based scheduling using:
  - `requestIdleCallback`
  - `IntersectionObserver`

## AEO Actions Taken

### Entity Grounding

- Reframed the homepage first viewport to clearly define the entity:
  - `PulseMeasurement is organisational intelligence software for live people signals.`
- Changed the homepage heading structure so the first visible product definition is the primary `H1`.
- Demoted the later value proposition heading from `H1` to `H2` to avoid multiple competing primary headings.
- Added an internal editorial rule that all pages must frame PulseMeasurement as organisational intelligence software, not as a medical pulse measurement term or generic survey tool.

### Structured Data

- Added homepage JSON-LD structured data with a connected schema graph:
  - `Organization`
  - `SoftwareApplication`
  - `WebSite`
  - `WebPage`
- Added explicit schema fields for:
  - product category
  - software description
  - organisation description
  - publisher and author relationship
  - homepage relationship to the software entity
  - logo
  - feature list
- Added `SoftwareApplication.featureList`, including:
  - Live People Signals
  - Confidence Scoring Analytics
  - Context Framing Engine
  - Multi-layered Feedback Architecture
  - Manager Intelligence Briefings
  - Closed-loop Action Tracking

### AI Crawler Access

- Updated `robots.txt` to explicitly allow major answer engine and AI discovery crawlers:
  - GPTBot
  - ChatGPT-User
  - ClaudeBot
  - PerplexityBot
  - Omgilibot
  - Applebot-Extended
  - CCBot
- Added the XML sitemap reference to `robots.txt`.

### AEO Content Hub

- Created and published a definition-first product page:
  - `what-is-pulsemeasurement.html`
- Created and published a FAQ page with `FAQPage` schema:
  - `faq.html`
- Created and published a glossary page with `DefinedTermSet` style content:
  - `glossary.html`
- Created and published an About page with trust, governance, and product context:
  - `about.html`
- Updated the resources hub:
  - `rich-information-at-scale.html`

### AEO Question and Use-Case Pages

Published dedicated answer-oriented pages for high-intent questions:

- `pulsemeasurement-vs-annual-engagement-surveys.html`
- `how-to-measure-employee-sentiment-in-real-time.html`
- `what-is-strategy-cascade-measurement.html`
- `how-to-detect-early-employee-attrition-risk.html`
- `how-to-detect-hidden-blockers-before-project-delays.html`
- `how-to-measure-goal-health-and-okr-integrity.html`
- `how-to-measure-burnout-and-capacity-strain.html`
- `how-to-create-manager-one-on-one-briefings.html`
- `what-is-an-ai-conversation-coach-for-employee-feedback.html`
- `how-to-measure-board-level-people-risk.html`
- `how-to-track-post-merger-integration-risk.html`
- `how-to-identify-emerging-leaders-from-work-signals.html`

These pages were written to support AI retrieval with:

- direct question-style titles
- clear first-answer paragraphs
- structured schema where appropriate
- internal links from the resources page
- sitemap inclusion

### Internal Editorial Guide

- Added `EDITORIAL_GUIDE.md` to preserve AEO-safe writing rules for future content.
- The guide covers:
  - always framing the noun
  - writing first sentences for direct retrieval
  - avoiding sentiment fluff
  - keeping first screens explicit
  - preserving trust and governance language

## Demo Flow SEO/AEO Relevance

- Changed the website demo journey from an immediate demo launch to a request-based flow.
- The website now captures:
  - user details
  - selected use-case questions
  - message/context
- The intended flow is:
  - user requests a guided demo
  - PulseMeasurement sends an email with a use-case summary
  - the link opens the beta demo instance with user details and selected journey context

This supports AEO by aligning demo entry points with answer-style use-case questions.

## Deployment Verification

The following deployment and verification actions were completed:

- Changes were committed to the `main` branch.
- Changes were pushed to GitHub.
- Azure Static Web Apps CI/CD completed successfully after each major batch.
- Live URLs were checked after deployment.
- The final live homepage was verified for:
  - schema presence
  - AI crawler directives
  - logo asset availability
  - deferred interactive initialization

## Relevant Commits

- `5b2efb3` - Add AEO definition page
- `e30859c` - Include sitemap and robots in static deploy
- `4e7d5e4` - Add AEO FAQ page
- `d2d0dca` - Add AEO glossary page
- `3015d95` - Add AEO about page
- `763acd0` - Add annual survey comparison page
- `9d69b28` - Add real-time sentiment guide
- `d1eb338` - Add strategy cascade measurement page
- `032b030` - Add early attrition risk guide
- `a38aa08` - Add hidden blocker detection guide
- `1b9d955` - Add goal health OKR guide
- `3588a04` - Complete AEO use case content hub
- `bd20116` - Strengthen homepage AEO entity signals
- `dfad094` - Refine AEO schema and editorial guide
- `6c00192` - Align AEO schema and crawler directives
- `692b37e` - Avoid non-composited UI transitions
- `66eb5f5` - Defer below-fold interactive initialization

## Recommended Next Steps

- Add `pulsemeasurement.com` to Google Search Console as a Domain property.
- Verify ownership using the DNS TXT record supplied by Google.
- Submit `https://pulsemeasurement.com/sitemap.xml`.
- Use URL Inspection to request indexing for the homepage, resource hub, FAQ, glossary, About page, and all AEO use-case pages.
- Monitor Search Console for indexing status, impressions, search queries, and page experience diagnostics.
