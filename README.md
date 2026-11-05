# Queen SusaStrategy Limited

Queen SusaStrategy is building an AI-led business strategy company to help teams find practical solutions to challenges across customer service, sales, finance, operations and decision-making. AI and machine learning are intended to sit at the centre of the strategy, grounded in business outcomes, suitable data, responsible design and human judgment.

The AI Opportunity Planner is the current local-first MVP and first step in that direction: a browser tool for structuring business challenges, assessing AI readiness and planning next steps. It is not a complete business-solution platform, live AI system or hosted service.

## Run locally

No build step or package install is required. Open `index.html` for the company site, or open `demo.html` to use the AI Opportunity Planner directly. The planner stores saved assessments in this browser only.

## AI Opportunity Planner MVP

- Capture a business name, sector, goal, challenge and business function.
- Assess available data, process consistency, potential impact, team readiness and decision sensitivity.
- Generate a transparent readiness score, use-case direction, data preparation guidance, evaluation measures and human-oversight notes.
- Save up to 20 assessments locally, reopen them, print a brief or download it as JSON.
- Clear saved assessments from the workspace.

The planner does not call, train or run a generative AI or machine-learning model. Its score and suggested use-case direction use an explicit rules-based rubric and fixed templates; they are not a technical feasibility study, ROI forecast or guarantee of results. Assessment information remains in browser `localStorage` and is not uploaded. Do not enter personal, confidential, customer-identifying, regulated or otherwise sensitive business information.

## Development and deployment boundary

This repository contains static HTML, CSS and JavaScript. It has no server, authentication, hosted workspace, AI-provider integration, model training or deployed infrastructure. Before handling real business data or offering hosted AI features, add a secured backend, identity and authorization, appropriate data governance, retention/deletion controls, monitoring, tested backups and validated human-reviewed AI workflows.

The About, Privacy and Terms pages should be reviewed against the company's actual legal and hosting arrangements before public launch.
