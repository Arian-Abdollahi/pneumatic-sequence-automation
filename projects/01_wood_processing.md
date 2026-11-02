# Wood-processing cylinder sequence

## Purpose

Coordinate clamping, machining, drilling, and release of a wooden workpiece with a timed pneumatic sequence.

| Stage | Intended action in the report |
| --- | --- |
| Start | Engage the holding cylinder(s) |
| Delay | Wait 1 second before the machining motion |
| Machining | Extend/hold the machining cylinder for 5 seconds, then retract |
| Drilling | Extend/hold the drilling cylinder for 5 seconds, then retract |
| Finish | Release the workpiece |

The detailed report groups the sequence as `3+ 4+ / 4- 2+ / 2- 3-`, with the indicated 1 s / 5 s / 5 s timing. `+` and `-` denote extension and retraction. Group transitions use the completion/end-position signal from the preceding group.

The introductory paragraph calls cylinders 1/3 clamps, 2 machining, and 4 drilling. Its detailed design instead uses cylinder 3 for holding, 4 for machining, and 2 for drilling. Follow the actual circuit labels when reproducing the design rather than treating those descriptions as identical.

Sources: original combined report pages 3-5, published pneumatic report pages 1-3; the first circuit file and supplied sequence photograph. The circuit-to-file association is based on numbering, not a new runtime inspection.

[Open circuit](../circuits/01_wood_processing.ct) · [Reference whiteboard](../assets/wood_sequence_whiteboard.jpg) · [Video slot](../videos/README.md)
