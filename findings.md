## Findings (agreed together, 20 minutes)

### Conflict Table (Run A(Sana ) vs Run B(Rida)

| Item ID | Answer A | Answer B | Same? | Agreed answer | Reason for difference |
| --- | --- | --- | --- | --- | --- |
| C-01 | No | No | Yes | No | - |
| C-02 | No | No | Yes | No | - |
| C-03 | No | No | Yes | No | - |
| C-04 | No | No | Yes | No | - |
| C-05 | No | No | Yes | No | - |
| C-06 | No | No | Yes | No | - |
| C-07 | No | No | Yes | No | - |
| C-08 | No | No | Yes | No | - |
| C-09 | No | No | Yes | No | - |
| C-10 | No | Yes | No | No | B counted R-10 (walk-in booking) as covering emergencies; R-10 says nothing about priority over scheduled patients. |
| C-11 | No | No | Yes | No | - |
| C-12 | No | Yes | No | No | B counted receptionist booking (R-10) as a way for offline patients; R-01 and R-10 do not say patients can book by phone or in person. |
| C-13 | No | No | Yes | No | - |
| C-14 | No | No | Yes | No | - |
| C-15 | No | No | Yes | No | - |
| C-16 | No | No | Yes | No | - |
| C-17 | No | No | Yes | No | - |
| C-18 | No | No | Yes | No | - |

### Real Problems in the SRS

| No. | Req ID | Problem | Type (vague / contradiction / missing) | Checklist item |
| --- | --- | --- | --- | --- |
| 1 | R-02 | "quickly" has no number or unit | vague | C-01 |
| 2 | R-12 | "normal working hours" is not defined | vague | C-02 |
| 3 | R-04, R-05 | Fixed 15-minute length conflicts with doctor-set 10-30 minutes | contradiction | C-03 |
| 4 | R-03 | No rule for two users booking the same slot at the same time | missing | C-04 |
| 5 | R-06 | Reminder timing and channel not stated | vague | C-05, C-06 |
| 6 | R-09 | "securely" has no measure; no roles allowed to view records | vague | C-07, C-08 |
| 7 | R-08 | "user-friendly for all age groups" is not measurable; elderly users not covered | vague | C-11 |
| 8 | R-10 | No priority rule for emergency walk-ins | missing | C-10 |
| 9 | R-01 | No booking option for patients without internet | missing | C-12 |
| 10 | R-14 | Doctors cannot block unavailable time | missing | C-13 |
| 11 | - | No requirement for the clinic administrator role | missing | C-15 |
| 12 | R-09 | No audit log of access to patient records (data protection officer) | missing | C-16 |
| 13 | R-11 | "active appointment" is not defined | vague | C-17 |
| 14 | R-13 | "clinic policy" is not stated or referenced | missing | C-18 |
| 15 | - | No peak-load requirement for busy Monday mornings | missing | C-09 |
