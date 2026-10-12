# AGENTS.md

This repository hosts the shared homepage and privacy policy for private, locally run personal tools
that use Google APIs.

- Keep only the minimum content needed to meet applicable Google requirements. Verify uncertain
  requirements against official Google sources; do not treat recommendations as mandatory.
- Protect the owner's privacy. Omit personal identifiers, app inventories, internal paths, architecture,
  and details of personal use unless a requirement makes them necessary. This applies to every file in
  this public repository, including these instructions.
- Keep wording short, plain, and accurate. Do not omit required disclosures or make unsupported claims
  about data handling, security, or Google's acceptance to reduce detail.
- Prefer one shared `index.html` and one shared `privacy.html`. Do not add app-specific pages or sections
  unless a concrete requirement or difference in data handling warrants them.
- Use durable wording so adding a tool does not require an edit when its data types, purposes, and
  handling are already covered. Update disclosures before introducing uncovered data use.
- Keep the public title `Personal Tools`. Do not add the owner's name, username, or contact details
  without a demonstrated requirement and the owner's approval.
- Keep both pages as static English HTML with a direct privacy link from the homepage. Preserve their
  URLs. Avoid scripts, analytics, external assets, build tools, and decorative content.
- Before delivery, review the disclosures against the actual tools, check links and HTML, and inspect
  the diff for unnecessary disclosure. State unresolved compliance uncertainty.
- Do not commit, push, or publish without explicit authorization. Obtain approval immediately before
  deploying changes to the live site.

Requirement references:
- https://developers.google.com/terms/api-services-user-data-policy
- https://support.google.com/cloud/answer/13807376
- https://support.google.com/cloud/answer/13806988
