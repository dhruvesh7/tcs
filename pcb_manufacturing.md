# PCB Manufacturing Defects - Electronics Assembly IQ

## 1. Solder Bridging
- **Description**: Unintended electrical connection between two adjacent conductive pads or traces.
- **Root Causes**:
    - Excessive solder paste volume.
    - Solder paste viscosity too low.
    - Improper stencil alignment or stencil thickness.
- **Parameters to Adjust**:
    - Decrease `Solder Paste Volume` (via stencil aperture).
    - Increase `Solder Paste Viscosity`.
    - Recalibrate `Stencil Alignment` system.
    - Check `Reflow Temperature Profile` (ramp rate too high).

## 2. PCB Delamination
- **Description**: Separation of the layers within the printed circuit board.
- **Root Causes**:
    - Moisture trapped within the pre-preg layers or core.
    - Laminate press temperature too low for the resin type.
    - Incompatible materials (Coefficient of Thermal Expansion mismatch).
- **Parameters to Adjust**:
    - Implement `Pre-bake Cycle` (120°C for 2 hours) to remove moisture.
    - Increase `Laminate Press Temperature`.
    - Verify `Press Pressure` is uniform across the panel.

## 3. Over-Etching (Trace Thinning)
- **Description**: The copper traces are thinner than designed or completely missing (open circuits).
- **Root Causes**:
    - Etchant concentration too high.
    - Conveyor speed through the etching machine too slow (immersion time too long).
- **Parameters to Adjust**:
    - Decrease `Etchant Concentration`.
    - Increase `Conveyor Speed`.
    - Adjust `Etch Factor` compensation in CAM data.

## 4. Drill Registration Offset
- **Description**: Holes (vias or mounting holes) are not centered on the pads.
- **Root Causes**:
    - Drill bit deflection due to excessive spindle speed.
    - Thermal expansion of the panel during the process.
    - Worn drill bits or spindle bearings.
- **Parameters to Adjust**:
    - Optimize `Spindle Speed` (RPM) for the bit diameter.
    - Use `Entry/Backup Boards` to stabilize the bit.
    - Replace `Drill Bits` every 1000 hits.
    - Implement `Panel Cooling` between cycles.
