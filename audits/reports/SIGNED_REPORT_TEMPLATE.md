# External Audit Signed Report Template

Use this template for every report linked from `/audits/STATUS.md` when `Status=Completed`.

## Metadata

- Audit-ID: `AUD-YYYY-NNN`
- Auditor: `<firm/legal-name>`
- Scope: `<paths/components>`
- Commit-Range: `<from..to>`
- Signed-Off: `yes`
- Auditor-Signature: `<reference or cryptographic signature id>`
- Signed-On: `YYYY-MM-DD`

## Summary

- Overall Result: `<pass/fail/conditional>`
- Critical Findings: `<count>`
- High Findings: `<count>`
- Medium Findings: `<count>`
- Low Findings: `<count>`

## Findings

| ID | Severity | Title | Affected Component | Status | Evidence |
|---|---|---|---|---|---|
| F-001 | High | Example finding | `contracts/ethereum/...` | Closed | `audits/remediation/<file>.md` |

## Sign-off Statement

I confirm the scope above was audited and this report is the final signed deliverable for the referenced commit range.

