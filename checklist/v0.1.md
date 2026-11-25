## Validation Checklist v0.1 (MediTrack SRS)

Rule: every item is Atomic, Observable, Unambiguous, Traceable. "Yes" is always the good answer.

| ID | Item | Answer | Evidence | Where question came from |
| --- | --- | --- | --- | --- |
| C-01 | Does every speed requirement state a number and a unit? | | | Rule: testable (R-02 "quickly") |
| C-02 | Does every availability requirement state specific hours or a percentage? | | | Rule: testable (R-12 "normal working hours") |
| C-03 | Is the document free of requirements that give different values for appointment length? | | | Rule: no contradictions (R-04 vs R-05) |
| C-04 | Does the document state what happens when two users request the same slot at the same time? | | | Risk 1: double booking |
| C-05 | Does the document state how many hours before an appointment a reminder is sent? | | | Risk 2: forgotten appointments |
| C-06 | Does the document name the channel (e.g. SMS or email) used for reminders? | | | Risk 2: forgotten appointments |
| C-07 | Does the document say which roles may view a patient's medical record? | | | Risk 3: privacy |
| C-08 | Does the document name a specific security measure for stored patient records? | | | Risk 3: privacy (R-09 "securely") |
| C-09 | Does the document state a peak load (number of users or bookings per minute) the system must handle? | | | Risk 5: busy Monday mornings |
| C-10 | Does the document state how an emergency walk-in is given priority over a scheduled patient? | | | Risk 4: emergency walk-ins |
| C-11 | Does the document state a measurable usability target for elderly patients (e.g. font size or accessibility standard)? | | | Risk 4: elderly patients (R-08 "user-friendly") |
| C-12 | Does the document describe how a patient without internet access can book an appointment? | | | User: Patient |
| C-13 | Does the document let doctors mark times when they are unavailable? | | | User: Doctor |
| C-14 | Does the document state which receptionist actions are allowed on an existing appointment (e.g. edit or reschedule)? | | | User: Receptionist |
| C-15 | Does the document describe how the clinic administrator adds or removes doctors? | | | User: Clinic administrator |
| C-16 | Does the document say that access to patient records is logged for audit? | | | User: Data protection officer |
| C-17 | Does the document define the term "active appointment"? | | | Rule: clear / unambiguous (R-11) |
| C-18 | Does every requirement that refers to a policy include the policy content or a reference to it? | | | Rule: complete (R-13 "clinic policy") |
