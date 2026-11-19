# Findings (agreed by A and B)

Comparison: A and B agreed on 17 of 18 items. The one difference was C-13
(A: No, B: N/A). We agreed on **No**, because R-10 is for walk-ins only and
gives no booking route for patients who cannot use the online system.

| # | Requirement | Problem | Type | Severity |
|---|-------------|---------|------|----------|
| 1 | R-02 | "quickly" has no number or unit | Not testable | High |
| 2 | R-04 vs R-05 | Fixed 15 minutes contradicts configurable 10 to 30 minutes | Contradiction | High |
| 3 | R-03 | Double booking is "prevented" but no rule for simultaneous booking | Incomplete | High |
| 4 | R-06 | No reminder time and no channel | Ambiguous | High |
| 5 | R-07 | "At any time" has no cancellation deadline | Ambiguous | Medium |
| 6 | R-08 | "User-friendly" is not measurable; elderly needs not covered | Not testable | High |
| 7 | R-09 | "Securely" has no method; no roles for viewing records | Ambiguous | High |
| 8 | R-10 | Walk-ins covered but emergency priority is missing | Incomplete | High |
| 9 | R-12 | "Normal working hours" is undefined | Ambiguous | Medium |
| 10 | R-13 | Refers to "clinic policy" that is not defined | Incomplete | Medium |
| 11 | Missing | No Monday morning load requirement | Missing | High |
| 12 | Missing | No requirements for Clinic administrator or Data protection officer | Missing | High |
| 13 | Missing | No rule for doctor absence or schedule changes | Missing | Medium |

## Notes
- Items marked "?" (C-06, C-08, C-11, C-13) need clearer wording in v0.2.
