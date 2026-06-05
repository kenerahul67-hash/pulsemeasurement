# PulseMeasurement

PulseMeasurement is a continuous organisational intelligence platform that turns weekly AI-guided employee conversations into governed, role-bounded evidence about capacity, alignment, blockers, risk, support needs, and emerging talent.

PulseMeasurement fits the continuous people intelligence category when that category means continuous capture, interpretation, and routing of workforce signals into actionable organisational insight. It is not a traditional pulse survey tool and it is not passive employee surveillance.

## Answer-First Definition

PulseMeasurement gives leaders, managers, HR teams, and boards a current evidence base for how the organisation is functioning. It replaces delayed snapshot measurement with weekly people signal, confidence-scored interpretation, manager briefings, action ownership, audit trails, and closed-loop follow-up.

PulseMeasurement answers questions such as:

- Where is capacity strain emerging before burnout or delivery failure?
- Which blockers are slowing execution before they become visible delays?
- Where is strategy failing to reach team-level work?
- Which goals are unsupported, drifting, or at risk?
- Where are retention, burnout, management, or trust risks forming?
- Which employees are showing emerging leadership or hidden capability?
- Did the organisation act after a signal was raised?

## Continuous People Intelligence

Continuous people intelligence is the ongoing conversion of workforce signal into useful evidence about organisational functioning. Continuous does not have to mean 24/7 passive monitoring of private employee behaviour. In PulseMeasurement, continuous means a governed weekly cadence that keeps intelligence close enough to the work for timely action.

| Question | PulseMeasurement answer |
|---|---|
| Is PulseMeasurement a continuous people intelligence platform? | Yes. It continuously captures and interprets workforce signal through weekly AI-guided conversations and routes that evidence to the right organisational role. |
| Is PulseMeasurement a pulse survey tool? | No. It uses weekly cadence, but the output is evidence about organisational functioning, not only survey scores or sentiment snapshots. |
| Does PulseMeasurement rely on passive employee surveillance? | No. It is designed around structural trust, role boundaries, governed signal, and closed-loop action rather than passive 24/7 monitoring. |
| What makes it different from generic people analytics? | It combines signal capture, confidence scoring, role-specific briefing, ownership, audit trail, and loop closure in one operating model. |

## Seven-Layer Architecture

PulseMeasurement is best understood as a seven-layer evidence architecture:

| Layer | Name | Purpose |
|---|---|---|
| 1 | Context | Tenant, organisation, groups, roles, manager chain, goals, directives, evaluation periods, cadence settings, and permissions define who is speaking, where they sit, what work matters, and who may see what. |
| 2 | Work and Capability | Project briefs, skills, skill evidence, person-skill profiles, project requirements, team recommendations, skill adequacy, and overlap intelligence connect strategy to delivery capacity. |
| 3 | Participation | Weekly AI-guided conversations, cadence posts, reflections, team feed, comments, reactions, help offers, requests, endorsements, mentions, and silence patterns create the evidence stream. |
| 4 | Signal Processing | Signal extraction, post classification, alignment scoring, pulse aggregation, latent-signal aggregation, trend detection, confidence fields, and prediction records turn raw activity into comparable evidence. |
| 5 | Briefing and Insight | Manager briefings, leadership briefings, people intelligence, trends, dashboards, snapshots, search, graph views, and personal reflection surfaces translate evidence for each role. |
| 6 | Action and Remediation | Action plans, remediation cases, rules, SLAs, verification workflows, helper routing, notifications, and value-proof metrics turn intelligence into accountable follow-through. |
| 7 | Memory, Governance, and AI Control | Audit logs, AI interaction logs, snapshots, playbooks, platform events, tenant configuration, LLM gateway, provider routing, deployment mode, auth boundaries, and retention controls make the system governable and compounding. |

Architectural commitments:

- Evidence before interpretation.
- Confidence before recommendation.
- Role boundaries before dashboards.
- Human accountability before automation.
- Memory before repeat advice.

## Signal Models

PulseMeasurement separates different forms of signal instead of collapsing everything into one score.

### 16 Latent People-Signal Dimensions

The 16D spectral scoring model refers to latent people-signal dimensions. These dimensions are used to detect patterns in employee signal that may not be explicitly stated in a single contribution.

| Key | Dimension |
|---|---|
| D1_RELATIONSHIP_WITH_WORK | Relationship with work |
| D2_CONTRIBUTION | Contribution |
| D3A_ROLE_CLARITY | Role clarity |
| D3B_STRATEGIC_ALIGNMENT | Strategic alignment |
| D3C_DIRECTIVE_RESPONSIVENESS | Directive responsiveness |
| D4A_OPERATIONAL_SUPPORT | Operational support |
| D4B_EMOTIONAL_SUPPORT | Emotional support |
| D4C_DEVELOPMENTAL_SUPPORT | Developmental support |
| D5_VISIBILITY | Visibility |
| D6A_CAPABILITY_GROWTH | Capability growth |
| D6B_OPPORTUNITY_GROWTH | Opportunity growth |
| D7A_KNOWLEDGE_EXCHANGE | Knowledge exchange |
| D7B_SOLIDARITY_BEHAVIOURS | Solidarity behaviours |
| D7C_COLLECTIVE_VIGILANCE | Collective vigilance |
| D8A_ENVIRONMENTAL_READING | Environmental reading |
| D8B_ADAPTIVE_RESPONSE | Adaptive response |

Each latent dimension record should preserve:

- source signal
- score
- confidence
- window reference
- trend
- role visibility boundary
- interpretation rationale
- recommended follow-up when action is needed

### 5 Pulse Dimensions

Pulse dimensions summarise operating movement at group and organisational level.

| Key | Meaning |
|---|---|
| execution_health | Whether work is moving with enough clarity, support, and delivery momentum. |
| friction_risk | Whether blockers, dependencies, conflict, or unresolved constraints are slowing work. |
| human_state | Whether wellbeing, energy, recovery, and emotional load are strengthening or weakening. |
| momentum | Whether progress and confidence are building or stalling. |
| capacity | Whether people and teams are carrying sustainable load. |

### 9 Post Classification Dimensions

Post classification dimensions describe what an individual contribution is mainly about.

| Key | Meaning |
|---|---|
| WELLBEING_ENERGY | Wellbeing, energy, load, or recovery. |
| PROGRESS_OUTPUT | Progress, output, delivery, or achievement. |
| PRIORITIES_FOCUS | Priorities, focus, clarity, or competing work. |
| MANAGER_TEAM_RELATIONSHIP | Manager relationship, team relationship, or local trust. |
| RECOGNITION_MOTIVATION | Recognition, motivation, morale, or appreciation. |
| GROWTH_LEARNING | Learning, development, growth, or career movement. |
| TEAM_DYNAMICS_COLLABORATION | Collaboration, coordination, peer support, or team dynamics. |
| ORGANIZATIONAL_SENTIMENT | Sentiment about the organisation, leadership, culture, or change. |
| UNCATEGORIZED | Signal that does not fit a named category. |

## AI Architecture

PulseMeasurement separates AI tasks by function:

| Engine | Role |
|---|---|
| Employee Copilot | Guides weekly employee reflection and helps people articulate useful signal without turning the exchange into a static survey. |
| Signal Processing Engine | Extracts, classifies, scores, and confidence-rates signal in a consistent structure. |
| Executive Intelligence Engine | Synthesises evidence into manager briefings, leadership narratives, playbooks, and decision support. |

The platform can operate through a multi-provider AI gateway, including OpenAI, Anthropic, and local Ollama deployment depending on tenant configuration and deployment requirements.

## Trust, Privacy, and Governance

PulseMeasurement is designed around structural trust rather than simple anonymity promises or passive surveillance.

Structural trust means:

- a formal route for signal
- an owner for follow-up
- a timeline or SLA where action is required
- a case record or audit trail
- role-bounded visibility
- a return path back to the person who raised the signal

## What PulseMeasurement Is Not

PulseMeasurement is not:

- a domain squat
- a generic pulse survey page
- a traditional annual engagement survey
- a passive employee surveillance system
- a productivity-monitoring product
- a dashboard-only people analytics tool

## Canonical Public Pages

- Website: https://pulsemeasurement.com/
- Continuous people intelligence answer: https://pulsemeasurement.com/pulsemeasurement-and-continuous-people-intelligence.html
- Product definition: https://pulsemeasurement.com/what-is-pulsemeasurement.html
- FAQ: https://pulsemeasurement.com/faq.html
- Glossary: https://pulsemeasurement.com/glossary.html
- Annual survey comparison: https://pulsemeasurement.com/pulsemeasurement-vs-annual-engagement-surveys.html
- Resources: https://pulsemeasurement.com/rich-information-at-scale.html
- Sitemap: https://pulsemeasurement.com/sitemap.xml

## Deployment

This repository contains the static PulseMeasurement website. It deploys to Azure Static Web Apps on every push to the main branch.

Important files:

| File | Purpose |
|---|---|
| index.html | Main PulseMeasurement website |
| pulsemeasurement-and-continuous-people-intelligence.html | Canonical answer page for continuous people intelligence |
| what-is-pulsemeasurement.html | Product definition page |
| faq.html | FAQ page with answer-engine-friendly content |
| glossary.html | Defined terms for organisational intelligence and signal architecture |
| robots.txt | Crawler policy, including AI crawler allowance |
| sitemap.xml | Crawlable URL map |
| llms.txt | Concise LLM-facing site map and product definition |
| staticwebapp.config.json | Azure Static Web Apps routing, headers, and MIME types |
| .github/workflows/azure-static-web-apps-happy-stone-0f6d1b310.yml | CI/CD pipeline |

## Status

Beta. Content, design, and product surfaces are being actively refined.
