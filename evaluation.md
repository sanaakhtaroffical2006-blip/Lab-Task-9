# Validation Checklist v0.1 (MediTrack SRS)

**Rule:** every item is Atomic, Observable, Unambiguous, Traceable. "Yes" is always the good answer.

**Legend:** `No*` = inferred from the checklist's own source note (the SRS requirement cited there is vague or conflicting). `Pending` = must be checked against the SRS text.

| ID | Item | Answer | Evidence | Where question came from |
|----|------|--------|----------|--------------------------|
| C-01 | Does every speed requirement state a number and a unit? | No* | R-02 uses "quickly" with no number or unit | Rule: testable (R-02 "quickly") |
| C-02 | Does every availability requirement state specific hours or a percentage? | No* | R-12 uses "normal working hours" with no specific hours | Rule: testable (R-12 "normal working hours") |
| C-03 | Is the document free of requirements that give different values for appointment length? | No* | R-04 and R-05 give conflicting appointment lengths | Rule: no contradictions (R-04 vs R-05) |
| C-04 | Does the document state what happens when two users request the same slot at the same time? | Pending | | Risk 1: double booking |
| C-05 | Does the document state how many hours before an appointment a reminder is sent? | Pending | | Risk 2: forgotten appointments |
| C-06 | Does the document name the channel (e.g. SMS or email) used for reminders? | Pending | | Risk 2: forgotten appointments |
| C-07 | Does the document say which roles may view a patient's medical record? | Pending | | Risk 3: privacy |
| C-08 | Does the document name a specific security measure for stored patient records? | No* | R-09 says only "securely" | Risk 3: privacy (R-09 "securely") |
| C-09 | Does the document state a peak load (number of users or bookings per minute) the system must handle? | Pending | | Risk 5: busy Monday mornings |
| C-10 | Does the document state how an emergency walk-in is given priority over a scheduled patient? | Pending | | Risk 4: emergency walk-ins |
| C-11 | Does the document state a measurable usability target for elderly patients (e.g. font size or accessibility standard)? | No* | R-08 says only "user-friendly" | Risk 4: elderly patients (R-08 "user-friendly") |
| C-12 | Does the document describe how a patient without internet access can book an appointment? | Pending | | User: Patient |
| C-13 | Does the document let doctors mark times when they are unavailable? | Pending | | User: Doctor |
| C-14 | Does the document state which receptionist actions are allowed on an existing appointment (e.g. edit or reschedule)? | Pending | | User: Receptionist |
| C-15 | Does the document describe how the clinic administrator adds or removes doctors? | Pending | | User: Clinic administrator |
| C-16 | Does the document say that access to patient records is logged for audit? | Pending | | User: Data protection officer |
| C-17 | Does the document define the term "active appointment"? | No* | R-11 uses the term without a definition | Rule: clear / unambiguous (R-11) |
| C-18 | Does every requirement that refers to a policy include the policy content or a reference to it? | No* | R-13 says "clinic policy" with no content or reference | Rule: complete (R-13 "clinic policy") |

## Summary

- Inferred "No": C-01, C-02, C-03, C-08, C-11, C-17, C-18 (7 items)
- Pending SRS check: C-04, C-05, C-06, C-07, C-09, C-10, C-12, C-13, C-14, C-15, C-16 (11 items)

## How to complete

1. Open the MediTrack SRS.
2. For each `Pending` row, answer Yes/No and paste the requirement ID or quote in **Evidence**.
3. Confirm each `No*` by quoting the exact SRS wording in **Evidence**, then remove the `*`.
