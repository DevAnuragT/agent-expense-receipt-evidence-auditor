# Expense Receipt Evidence Auditor

Check expense claims for receipt evidence, purpose, date, and policy references.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-expense-receipt-evidence-auditor.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
