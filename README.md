\# WFSL Sentinel — Branch Policy



\## Purpose



This repository defines the \*\*branch protection and change-control sentinel\*\*

for Wynergy Fibre Solutions Ltd (WFSL).



It specifies mandatory source-control behaviour for any repository that

operates within the WFSL portfolio boundary.



This repository is \*\*normative\*\*. It defines required behaviour, not guidance.



---



\## Sentinel Role



The sentinel layer exists to:



\- Enforce disciplined change control

\- Prevent silent mutation of history

\- Preserve auditability and intent

\- Provide a behavioural reference point across the portfolio



Sentinel repositories do not deliver products.

They constrain how products are changed.



---



\## Mandatory Branch Rules



For any repository governed by WFSL sentinel policy:



\- A single primary branch MUST exist (`MAIN` or `main`)

\- The primary branch MUST be protected

\- Direct pushes to the primary branch MUST be disabled

\- All changes MUST be made via pull request

\- Pull requests MUST be scoped to a single intent

\- History MUST be consolidated (squash or equivalent)



There are no exceptions based on urgency or convenience.



---



\## Pull Request Discipline



Each pull request MUST:



\- Represent one clear intent

\- Be reviewable in isolation

\- Avoid mixed or unrelated changes

\- Leave the repository in a valid, inspectable state



Pull requests function as \*\*change records\*\*, not just merge mechanisms.



---



\## Merge Strategy



Approved strategies:



\- Squash merge (preferred)

\- Rebase and merge (only where linear history is required)



Merge commits that obscure intent are discouraged.



---



\## Local Divergence Handling



Local divergence from the canonical remote branch is expected.



When divergence occurs:



\- The remote primary branch is authoritative

\- Local history MUST be reconciled to match the remote

\- Force-push to protected branches is prohibited



Reconciliation is a developer responsibility.



---



\## CI Expectations



Sentinel policy expects that governed repositories:



\- Use minimal CI

\- Detect structural or integrity issues

\- Avoid decorative or fragile automation



CI exists to preserve integrity, not to simulate compliance.



---



\## Non-Assertions



This repository does NOT:



\- Claim regulatory compliance

\- Assert certification or approval

\- Replace legal or contractual controls

\- Describe operational capability



It defines behavioural constraints only.



---



\## Audience



This repository is intended for:



\- Engineers

\- Reviewers

\- Auditors

\- Inspectors

\- Counterparties assessing governance posture



It is not a marketing artefact.



---



\## Status



Normative. Stable. Slow-moving.



Changes to this repository affect expected behaviour across the WFSL portfolio

and therefore require elevated scrutiny.



