# sukis001

Security researcher and bug bounty hunter based in Indonesia.

I hunt web and API vulnerabilities, with a focus on the deep surfaces most
hunters skip: business logic, authorization boundaries, and neglected flows.

## Where to find me

- **Intigriti** — luascok
- **HackerOne** — luascok
- **YesWeHack** — luascok
- **X** — [@luascok](https://x.com/luascok)

## Focus areas

- Web and API security testing
- Business-logic flaws: limit and quota enforcement, pricing and state abuse
- Authorization testing: cross-tenant isolation, object-level access control,
  stale authorization after role changes
- Neglected flows: account recovery, email change, invitations, export and
  sharing features, legacy API versions
- API key scoping and permission boundaries

## Approach

- Deep surfaces over surface scans — the easy findings are usually already
  taken.
- Every hypothesis gets a falsification test, not just a confirmation attempt.
- Cross-tenant claims are only made with paired positive controls.
- Reports ship with sanitized request/response evidence and an explicit
  confidence label.

## On this account

- [bug-bounty-methodology](https://github.com/sukis001/bug-bounty-methodology)
  — my working notes on how I hunt and report.
- [hypothesis-ledger](https://github.com/sukis001/hypothesis-ledger)
  — a small CLI for tracking security-research hypotheses with pre-registered
  falsification criteria.
