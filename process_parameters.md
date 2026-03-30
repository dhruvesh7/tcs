# Process Parameters Correlation Guide

| Manufacturing Process | Parameter | Impact if Too High | Impact if Too Low | 
|-----------------------|-----------|--------------------|-------------------|
| **Injection Molding** | `Injection Speed` | Surface Burns, Flash | Short Shots, Sink Marks |
| **Injection Molding** | `Melt Temp` | Material Degradation | Delamination, Cold Slugs |
| **Injection Molding** | `Pack Pressure` | Over-packing, Flashing | Voids, Brittle Parts |
| **CNC Machining** | `Spindle Speed` | Tool Overheating | Chatter Marks, Rough Surface |
| **CNC Machining** | `Feed Rate` | Tool Breakage | Built-up Edge (BUE) |
| **Metal Casting** | `Pouring Temp` | Gas Porosity | Cold Shuts (Miss-runs) |
| **Metal Casting** | `Mold Vents` | N/A | Gas Traps (Bubbles) |

## Root-Cause Investigation Framework
Use this framework to diagnose issues:
1.  **Observe the Defect**: Identify the symptom (e.g., "Silver Streaks").
2.  **Check Primary Parameter**: Look at the parameter most likely to cause it (e.g., `Injection Speed`).
3.  **Cross-Check Secondary Factors**: (e.g., `Resin Moisture`).
4.  **Confirm Alignment**: Verify against the material's data sheet.
