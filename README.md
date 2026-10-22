# neXus
Brand governance platform that explains issues, not just rejects content.
Live demo: https://404brain-null.github.io/neXus/
neXus reviews content before it is published. It checks drafts against approved guidelines, a claims library and the brand palette, explains every issue with a reason, a source and a rewrite, and routes content through a human approval workflow with a full audit log.

Try it in 2 minutes
Open the live demo. A sample draft is preloaded.
Click Run brand check, then Accept all suggested fixes.
Click Submit for approval.
Switch "Signed in as" to Authorised reviewer, open Review queue and Approve.
Switch back to Creator and Publish. Check Insights and Audit log.
Features
Six checks: tone, terminology, messaging, visual consistency, accessibility, unsupported claims
Reason, source citation and suggested rewrite for every flag
Uncertain claims are marked "needs human" and routed to a reviewer
WCAG contrast, alt text, link text and sentence-length checks; palette and font checks
Roles: Creator, Manager, Authorised reviewer, with risk-based routing
Approve, request changes, escalate, reopen, publish
Editable guidelines library, insights dashboard, audit log
Tech

Single-file web app (HTML, CSS, vanilla JavaScript). Rules engine over an editable approved-rules library. State is kept in the browser (localStorage). Hosted on GitHub Pages. No build step: open index.html.

Known limitations

Rule-based only (no language model yet); roles are simulated; data is per-browser; no file upload; no integrations.

Round 3
Language-model explainer with retrieval over uploaded guidelines
File and design ingestion (DOCX, PPTX, PDF, images)
Real accounts, shared database and tracked-changes version history
