# Quality, Data and Validation Guidelines

## Purpose

Keep the library accurate, reproducible, ethical, and transparent about what has and has not been completed.

## Data sourcing and privacy

1. Prefer synthetic datasets or public datasets with clear reuse rights.
2. Record the original source, access date, license or usage restrictions, and any modifications.
3. Do not commit client records, personal identifiers, proprietary financial records, access tokens, or credentials.
4. Label invented examples **hypothetical** or **synthetic**.
5. Do not imply that a synthetic result is a real business finding.

## Formula and KPI verification

- State the business question, metric definition, numerator, denominator, units, and time period.
- Show inputs and a reproducible calculation.
- Check arithmetic independently; include edge cases such as zero denominators and missing data.
- Explain interpretation, assumptions, and limitations.
- Distinguish accounting revenue, booked orders, cash received, and other different measures.

## Python and SQL verification

- Identify Python version, packages, or SQL dialect and database version where relevant.
- Provide sample input or a reproducible schema and data.
- Include expected output, and compare it with actual executed output before labeling verified.
- For SQL joins, document row grain, join keys, row counts, and duplicate risks.
- For code, explain error handling and edge cases when relevant.
- Never label an unexecuted example as tested.

## Dashboards and case studies

- Identify audience, question, KPI definitions, source fields, refresh assumptions, and filters.
- Reconcile totals against source data.
- Describe what findings support and what they cannot establish.
- Separate observations from recommendations and predicted benefits from measured outcomes.

## Learning status

- **Planned:** Not started.
- **Draft:** Written but not verified.
- **Guided practice:** Completed with instructional assistance.
- **Independent practice:** Attempted without step-by-step instructions.
- **Verified:** Output checked and reproducible instructions recorded.

## Publication checklist

- [ ] Appropriate folder and descriptive filename
- [ ] Sources and permissions documented
- [ ] Sensitive data removed
- [ ] Examples reproducible
- [ ] Results checked before claiming verification
- [ ] Assumptions and limitations stated
- [ ] Learning status accurate
- [ ] Links work

## Licensing note

No open-source license is added automatically. The repository owner should decide whether code, educational text, and future commercial templates will have the same reuse terms before selecting a license.

[← Back to main README](README.md)
