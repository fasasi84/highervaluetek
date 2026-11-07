# Queen SusaStrategy Limited

Queen SusaStrategy is developing an AI-powered business and financial intelligence workspace for SMEs in Nigeria. The functional sample-workspace MVP includes a financial snapshot, what-if scenarios, a local ordinary least-squares revenue trend, deterministic recommendations, cash-flow scenarios, people-cost signals, and CSV/print-to-PDF reports.

The dashboard uses editable sample figures and deterministic rules. It is not a live AI service, accounting system, hosted application, or source of financial advice. It has no accounts, data upload, backend, persistence, or payment processing.

## Run locally

No build step or package install is required. Open `index.html` for the Get Started page, `dashboard.html` for the SME intelligence workspace, or `data-services.html` for the product overview. The Get Started page links to the workspace; the legacy `demo.html` URL redirects to the dashboard.

## Product overview

- Target users: Nigerian SMEs without dedicated finance teams; planned market entry in Abuja, followed by expansion across Nigeria and later international markets.
- Prototype focus: editable monthly revenue, costs, payroll, cash balance, and team-size assumptions.
- Outputs: gross margin, operating profit, a locally trained regression forecast, rule-based recommendations, people-cost signals, and CSV/print reports.
- Intended commercial model: monthly B2B SaaS subscriptions and enterprise packages with enhanced reporting and team-level intelligence. Pricing, onboarding, and billing are not configured.
- Market stage: MVP development and validation through SME pilot discussions; no commercial deployment is claimed.
- Planned Azure use, subject to credits and deployment: SaaS hosting, secure data storage, authentication and organization/role permissions, Azure OpenAI, forecasting, and scenario analysis.

## Microsoft startup criteria readiness

The criteria below are evidence notes, not a claim of Microsoft eligibility or approval. Confirm the current program's rules and provide supporting documentation.

| Criterion | Current evidence |
| --- | --- |
| AI/ML-powered product | The prototype fits a linear-regression trend to monthly revenue history in the browser. It is a small, transparent ML model, not generative AI or a production service. |
| B2B SaaS model | Recurring business subscriptions and enterprise packages are the intended model. Hosted accounts, billing, and customer subscriptions are not live. |
| MVP stage or beyond | An interactive financial prototype exists; it is not a deployed multi-customer application. |
| VC, accelerator, or angel-backed | Not evidenced in this repository; founders must confirm and document. |
| Technical co-founder or CTO | The company site says a technical lead has not yet been appointed. |
| Repeat founder | Not evidenced in this repository; founders must confirm. |
| Underrepresented founder | Requires founder self-identification and confirmation against the program's definition. |
| $10,000+/month cloud usage | No cloud product infrastructure is deployed from this repository; provide current invoices if cloud usage exists elsewhere. |

## Infrastructure and data boundary

The dashboard runs locally in the browser. Scenario changes are held in page memory only and are discarded on reload. There is no hosted account system, uploaded data, production AI integration, cloud storage, or payment connection. Azure services and Azure OpenAI are planned, not deployed. Do not enter confidential or personal data.

The About, Privacy and Terms pages should be reviewed against the company's actual legal and hosting arrangements before publication.
