# Start Here

Signal Frontier is a portfolio prototype that demonstrates finance reporting-readiness review using fictional sample data and deterministic control logic.

## What to Review First

Start with these files:

1. `README.md` — Project overview, purpose, boundaries, and planned structure.
2. `data/sample_reporting_readiness_data.csv` — Fictional reporting input records used by the prototype.
3. `src/signal_frontier.py` — Python script that classifies each reporting item.
4. `outputs/` — Generated readiness summaries, control exceptions, and escalation items.
5. `docs/` — Supporting documentation for project logic, run instructions, and file structure.

## What the Prototype Does

Signal Frontier evaluates fictional reporting records for:

- Missing legal entity
- Missing source system
- Ledger/subledger variance
- Materiality threshold breaches
- Certification status
- Data quality status
- Manual adjustment flags
- Exception aging
- Escalation conditions

Each record is classified as:

- `Ready`
- `Review Required`
- `Blocked`
- `Escalate`

## What the Prototype Does Not Do

Signal Frontier does not produce regulatory reports, interpret laws or regulations, automate compliance decisions, or claim regulatory sufficiency.

It supports reporting-readiness review only.

Final interpretation remains with Finance, Risk, Compliance, Legal, or authorized business reviewers.

## Suggested Review Path

For a business reviewer:

1. Read `README.md`.
2. Review the sample data.
3. Review `docs/control_logic.md`.
4. Review the generated output files.

For a technical reviewer:

1. Read `README.md`.
2. Review `requirements.txt`.
3. Review `src/signal_frontier.py`.
4. Run the script locally if desired.
5. Compare generated outputs to the documented logic.

## Current Status

Work in progress.
