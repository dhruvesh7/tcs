# Sheet Metal Stamping Defects - Manufacturing Intelligence

## 1. Wrinkling
- **Description**: Wavy deformation of the sheet metal, typically on the flange or side walls.
- **Root Causes**:
    - Blank holder pressure (BHP) too low (metal flows too freely).
    - Draw beads geometry too shallow.
- **Parameters to Adjust**:
    - Increase `Blank Holder Pressure`.
    - Adjust `Cushion Pressure` in the press.
    - Check `Lubricant viscosity`.

## 2. Springback
- **Description**: The Tendency of the metal to return to its original shape after forming.
- **Root Causes**:
    - Low yield strength in the material.
    - Large punch radius.
- **Parameters to Adjust**:
    - Increase `Overbend Angle`.
    - Reduce `Punch Radius`.
    - Increase `Blank Holder Pressure`.

## 3. Cracking (Tearing)
- **Description**: Sudden failure of the material during drawing, typically at the bottom or corners.
- **Root Causes**:
    - Excessive blank holder pressure (stretching too much).
    - Insufficient lubrication.
- **Parameters to Adjust**:
    - Decrease `Blank Holder Force`.
    - Apply `High-Viscosity Lubricant`.
    - Reduce `Draw Speed`.
    - Increase `Die Entry Radius`.
    - Check `Material Grain Direction`.
