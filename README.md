# Noble Foods HR Service Hub

An interactive Freshservice-style HR ticketing mockup. This is a standalone website mockup using fictional records. It is not connected to any HR, payroll, Microsoft or Freshservice system.

## Explore the site

Open `index.html` in a modern browser, or publish this folder with GitHub Pages. No installation or build is needed. All links and assets use relative paths, including when the site runs beneath a repository name.

Start on the employee portal and choose a request type.

1. Choose a service and select **Load example**.
2. Review and submit the fictional request.
3. Track the request, or switch to the HR workspace.
4. Assign an adviser and change the status.
5. Add a private HR note and a requester reply.
6. Record a resolution and switch back to the employee view.
7. Explore reporting or download a CSV snapshot.

The request catalogue includes weekly and salaried pay, new starter documents, probation reviews, changes to details, leavers, maternity, paternity, holiday, other leave, absence and fit notes, bereavement, purchase orders, egg deductions and a provisional RTW reporting request. ER remains a separate item for discussion.

## Demo boundaries

- Use fictional information only.
- Requests and changes stay in the current browser tab using session storage. They are not shared with other visitors.
- Selected attachments retain filenames and sizes only. File contents are never read or uploaded. The six linked sample PDFs are public fictional examples.
- Messages and approvals are simulated. No email is sent.
- Employee and HR views demonstrate a proposed experience. They are not authenticated roles or security controls.
- Private note text stays out of the employee conversation screen, but all demo data remains accessible in the browser. Do not use real confidential information.
- The CSV is a snapshot for Excel, not a live connection. It excludes employee details, documents, free-text descriptions and internal notes.
- **Reset demo** restores the original examples in this browser tab.

## Publish

Follow [DEPLOY-TO-GITHUB.md](DEPLOY-TO-GITHUB.md). Use an approved work organisation or account. The standard GitHub Pages address includes the repository owner's login. An organisation login or approved custom domain is required if the work account login contains a personal name you do not want in the URL.

## Files

- `index.html`: page structure
- `style.css`: branding and responsive layout
- `app.js`: request forms, demo tickets, conversations and reporting
- `forms.js`: forms library, digital records and attachment metadata
- `form-*.pdf`: five printable sample forms
- `example-overtime-completed.pdf`: fictional completed overtime record
- `logo.png`: supplied Noble Foods logo
- `colleagues.jpg`: AI-generated illustration of fictional colleagues
- `.nojekyll`: disables Jekyll processing when uploaded

## Editing

The request types and their fields are defined in the `categories` object near the top of `app.js`. The seeded example tickets are in `seed()`. Colours and layout are in `style.css`.

## Sources

The scope follows the supplied ideas photograph and discussion. The branding uses the supplied Noble Foods logo. The supporting colleague image is AI-generated and does not show actual Noble Foods colleagues or premises.

Freshservice product context:
https://www.freshworks.com/freshservice/business-teams/hr/
https://support.freshservice.com/support/solutions/articles/50000003768-get-started-onboarding-your-hr-teams-on-freshservice-fsbt

These are proposed layouts rather than screenshots of a configured Freshservice tenant. Features, permissions, licence requirements, records retention and integrations need validation before a live HR service.

## HR workspace and documents

Priority and due-by dates are manually editable in the team queue and ticket. An unresolved request is automatically flagged after more than 72 elapsed hours from receipt, including weekends and waiting time. A past due date is a separate flag.

Reporting shows received/processed tickets over the last seven UK calendar dates, average elapsed processing and first-response hours for recently resolved tickets, current status and open-request age. Unknown timestamps are excluded from averages. Reopening removes a ticket from completed totals until it is resolved again.

Forms & documents contains five sample templates with digital and paper routes. Digital answers remain structured on the ticket; no PDF is generated automatically. The paper route requires a completed scan example. The local file selector demonstrates up to five PDF/JPG/PNG files of 10 MB each, storing metadata only. These demo limits are not a statement of Freshservice limits.

These are illustrative templates, not approved Noble Foods documents. Typed names and checkboxes are not verified signatures or approvals. In Freshservice, use Service Catalog fields for digital answers, controlled PDF links for paper templates, attachment controls for scans and a separately configured approval process. Confirm subscription, portal version, permissions and document handling before implementation. Dedicated custom Attachment fields require the V2 requester portal.

Official references:
https://support.freshservice.com/support/solutions/articles/199643-configure-the-service-catalog
https://support.freshservice.com/support/solutions/articles/50000012680-custom-field-types-for-service-catalog-items
https://support.freshservice.com/support/solutions/articles/50000000619-can-i-make-attachments-mandatory-for-a-service-item-
