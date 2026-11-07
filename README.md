# Queen SusaStrategy Limited

Queen SusaStrategy is exploring a business and financial intelligence product for small-business owners and managers. The browser-only dashboard prototype includes an ordinary least-squares linear-regression revenue trend model trained on user-entered monthly history, deterministic recommendations, financial analysis, cash-flow scenarios, people-cost signals, and report exports.

The dashboard uses editable sample figures and deterministic rules. It is not a live AI service, accounting system, hosted application, or source of financial advice. It has no accounts, data upload, backend, persistence, or payment processing.

## Run locally

No build step or package install is required. Open `index.html` for the Get Started page, `dashboard.html` for the SME intelligence workspace, or `data-services.html` for the product overview. The Get Started page links to the workspace; the legacy `demo.html` URL redirects to the dashboard.

## Product overview

- Target users: small-business owners and managers, initially in Nigeria.
- Prototype focus: editable monthly revenue, costs, payroll, cash balance, and team-size assumptions.
- Outputs: gross margin, operating profit, a locally trained regression forecast, rule-based recommendations, people-cost signals, and CSV/print reports.
- Intended commercial model: recurring monthly B2B SaaS subscriptions and enterprise packages; pricing and billing are not configured.

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

The dashboard runs locally in the browser. Scenario changes are held in page memory only and are discarded on reload. There is no AI integration, cloud storage, account system, uploaded data, or payment connection. Do not enter confidential or personal data.

The About, Privacy and Terms pages should be reviewed against the company's actual legal and hosting arrangements before publication.
