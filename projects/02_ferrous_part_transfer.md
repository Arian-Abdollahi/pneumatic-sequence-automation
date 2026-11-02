# Ferrous-part transfer sequence

## Purpose

Use four pneumatic cylinders to hold a box, pick up ferrous parts with a magnetic pickup arrangement, transfer them to another position, deposit them, and operate a final guiding actuator.

| Cylinder | Role described in the report |
| --- | --- |
| A | Hold the box/workpiece |
| B | Vertical pickup/deposit motion |
| C | Horizontal transfer motion |
| D | Guide or eject parts after transfer |

The report's four cascade groups are `D- A+ B+ / B- A- C+ / B+ C- / B- D+`. This is a transcription of its grouping diagram, not a newly simulated motion trace. Confirm motion overlap and end-position transitions in the actual FluidSIM circuit.

The separate whiteboard photograph contains revisions and does not match every terminal annotation in the report. Both references are retained without silently substituting one sequence for the other.

Sources: original combined report pages 6-8, published pneumatic report pages 4-6, and the second supplied circuit/whiteboard files. The original report contains the valve and sensor details.

[Open circuit](../circuits/02_ferrous_part_transfer.ct) · [Reference whiteboard](../assets/transfer_sequence_whiteboard.jpg) · [Video slot](../videos/README.md)
