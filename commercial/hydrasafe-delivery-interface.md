# ReactorOps → HydraSafe Delivery Interface

## Purpose
Define the reactor-documentation inputs required for a facility-level HydraSafe permitting-readiness engagement.

## Required intake
1. Facility and project identifier.
2. Reactor manufacturer, model, serial or asset identifier, and quantity.
3. Process classification: CVD, HPHT, or other documented process.
4. OEM manuals, installation requirements, gas specifications, interlocks, shutdown instructions, and maintenance requirements.
5. Commissioning, inspection, maintenance, alarm-test, and training records.
6. Existing operating, startup, shutdown, abnormal-condition, and emergency procedure references.
7. Open deviations, expired inspections, missing records, and unresolved owner/OEM questions.

## Output record
For each reactor or homogeneous reactor bank, ReactorOps returns:
- document-present/document-missing status;
- source and revision;
- responsible external reviewer;
- lifecycle stage;
- evidence pointer;
- gap severity for documentation triage;
- required next action;
- disposition.

## Prohibited representations
This interface does not certify equipment, determine code compliance, approve commissioning, authorize operation, replace OEM requirements, or provide a professional engineering opinion.

## Commercial use
The output is an input to HydraSafe's free gap assessment and paid facility packet. It may support a PE/AHJ/insurer review but cannot substitute for that review.
