# Noble Foods HR Service Hub

An interactive proposal for a Freshservice HR ticketing experience. This is a standalone website mockup using fictional records. It is not connected to any HR, payroll, Microsoft or Freshservice system.

## Explore the site

Open `index.html` in a modern browser, or publish this folder with GitHub Pages. No installation or build is needed. All links and assets use relative paths, including when the site runs beneath a repository name.

Start with **Try the employee journey**, or use **Start guided pay example** on the proposal page.

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
- File attachments are example filenames. No files are uploaded or read.
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
- `app.js`: forms, demo tickets, conversations and reporting
- `logo.png`: supplied Noble Foods logo
- `colleagues.jpg`: AI-generated illustration of fictional colleagues
- `proposal.pptx`: click-through PowerPoint proposal
- `.nojekyll`: disables Jekyll processing when uploaded

## Editing

The request types and their fields are defined in the `categories` object near the top of `app.js`. The seeded example tickets are in `seed()`. Colours and layout are in `style.css`.

## Sources

The scope follows the supplied ideas photograph and discussion. The branding uses the supplied Noble Foods logo. The supporting colleague image is AI-generated and does not show actual Noble Foods colleagues or premises.

Freshservice product context:
https://www.freshworks.com/freshservice/business-teams/hr/
https://support.freshservice.com/support/solutions/articles/50000003768-get-started-onboarding-your-hr-teams-on-freshservice-fsbt

These are proposed layouts rather than screenshots of a configured Freshservice tenant. Features, permissions, licence requirements, records retention and integrations need validation before a live HR service.
