# Higher Value Teknical

Reliability Desk is an early, local-first maintenance-planning product prototype for industrial maintenance teams. It includes a marketing site and a browser dashboard; it is not a hosted or production system.

## Run locally

No build step or package install is required. Open `index.html` in a browser, or open `demo.html` to work directly in the dashboard. The company site links to the demo and includes the same dashboard embedded on the homepage.

## Current prototype workflows

- Add, edit and delete locally created equipment assets with an ID, type, area, service date and condition note. The six fictional seed assets are immutable.
- Import an asset catalog from CSV. Required headers: `Asset ID`, `Asset`, `Type`, `Area`. Optional headers: `Last service`, `Latest signal`, `Severity` (integer 1-5). Quoted fields and commas inside quoted values are supported.
- Record inspections, service, repairs or failures with a date, severity and notes; remove an incorrectly logged event and recalculate its sample priority.
- Search/filter assets, mark records reviewed, add follow-up notes, and export filtered assets as CSV.
- Export or restore a JSON workspace backup.

The six seeded assets are fictional. All user-entered records, events, notes and review state are stored in browser `localStorage` and are not uploaded. Use JSON backup to move data between browsers. Reset workspace clears local records and activity.

## Score behavior

Seed records have illustrative fixed scores. Once a record has logged events, its sample score is recalculated as `min(100, 15 + 12 * highest recorded severity + 8 * min(event count, 5))`. Priority is Low below 38, Medium from 38 through 64, and High from 65. This rule is demonstrative only; it is not validated for equipment-risk decisions and is not AI.

## Production readiness boundary

The current implementation has no server, authentication, shared workspaces, role-based access, audit-grade history, remote backups, equipment/CMMS integrations, telemetry processing, or deployed AI. Do not enter personal, confidential, or safety-sensitive operational data. Before a production pilot, add a secured backend and database, identity and authorization, tenant isolation, encryption and key management, audited migrations, retention/deletion controls, monitoring, tested backups, data-processing agreements, and validated human-reviewed analysis. AWS, Azure and NVIDIA are only planned evaluation options; no infrastructure is deployed by this repository.

The About, Privacy and Terms pages should be reviewed against the company’s actual legal and hosting arrangements before public launch.