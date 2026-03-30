# Manufacturing Defects Catalog - Discrete Manufacturing

## 1. Injection Molding Defects

### Surface Burns (Silver Streaks)
- **Description**: Silver or brown marks appearing on the surface of the molded part.
- **Root Causes**: 
    - Injection speed too high (causing friction).
    - Melt temperature above recommended range for the material.
    - Moisture in the resin (poor drying process).
- **Parameters to Adjust**:
    - Reduce `Injection Speed`.
    - Decrease `Barrel Temperature`.
    - Check `Resin Moisture Content` and ensure `Dryer Temp` is 80°C for 4 hours.

### Short Shots
- **Description**: The part is incomplete because the molten plastic didn't fill the entire cavity.
- **Root Causes**:
    - Injection pressure too low.
    - Injection stroke too short.
    - Low material temperature.
- **Parameters to Adjust**:
    - Increase `Injection Pressure`.
    - Adjust `Cushion Size` (ensure stroke is sufficient).
    - Increase `Nozzle Temperature`.

## 2. CNC Milling & Machining Defects

### Chatter Marks (Vibration)
- **Description**: Wavy or irregular patterns on the surface of the machined part.
- **Root Causes**:
    - Feed rate too high for the spindle speed.
    - Tool rigidity low or tool overhang too long.
    - Worn spindle bearings.
- **Parameters to Adjust**:
    - Decrease `Feed Rate`.
    - Increase `Spindle Speed` (RPM).
    - Reduce `Depth of Cut`.

### Built-up Edge (BUE)
- **Description**: Pieces of the workpiece material adhering to the cutting edge of the tool.
- **Root Causes**:
    - Cutting speed too low.
    - Inadequate coolant flow.
- **Parameters to Adjust**:
    - Increase `Cutting Speed`.
    - Adjust `Coolant Flow Rate`.
    - Use tool with `Anti-friction Coating`.

## 3. Metal Casting Defects

### Porosity (Gas Holes)
- **Description**: Small holes or bubbles on the surface or within the casting.
- **Root Causes**:
    - High moisture in the sand mold.
    - High pouring temperature.
- **Parameters to Adjust**:
    - Decrease `Pouring Temperature`.
    - Increase `Mold Venting`.
    - Reduce `Moisture Content` in sand.
