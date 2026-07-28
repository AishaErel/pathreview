## Week 7 — Issue selection

**Issue link:** https://github.com/ascherj/pathreview/issues/117

**Issue title:** API docs don't include example curl commands
#117
**Issue link:** https://github.com/ascherj/pathreview/issues/117

**Issue title:** API docs don't include example curl commands #117

**Tier:** [X] Tier 1 [ ] Tier 2 [ ] Tier 3
**Tier:** [X] Tier 1 [ ] Tier 2 [ ] Tier 3

**Problem summary:**
The API documentation explains the available endpoints but does not include example `curl` commands for testing them. This makes it harder for developers who are setting up the project for the first time to verify that the API is running correctly. Adding example `curl` commands will provide an easy way to test each endpoint.
**Branch name:** docs/117-API-docs-issue

**Setup confirmation:** [] App does not run locally at localhost:5173 because of errors and issues which will be dealt with later by
The API documentation explains the available endpoints but does not include example `curl` commands for testing them. This makes it harder for developers who are setting up the project for the first time to verify that the API is running correctly. Adding example `curl` commands will provide an easy way to test each endpoint.
**Branch name:** docs/117-API-docs-issue

**Cohort ledger:** [X] Yes, Issue added to cohort ledger
**Setup confirmation:** [] App does not run locally at localhost:5173 because of errors and issues which will be dealt with later by

**Cohort ledger:** [X] Yes, Issue added to cohort ledger

## Week 8 — Reproduction & solution planning

**Reproduction commit link:** [link to commit documenting the reproduced issue]

**Reproduction summary:**
I started the application locally and successfully tested the POST /auth/register and POST /auth/login endpoints using curl. Although the endpoints work, docs/API.md does not provide example curl commands, requiring new developers to determine the request syntax themselves.

**PLAN.md link:** https://github.com/AishaErel/pathreview/blob/docs/117-API-docs-issue/PLAN.md

**Walkthrough video (recommended):**

**Blockers or open questions:**
