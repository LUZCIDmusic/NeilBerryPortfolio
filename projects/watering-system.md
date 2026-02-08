# Automated Plant Watering System (Raspberry Pi + Soil Moisture + Solenoids)

**Type:** Personal Project  
**Focus:** Embedded control • Sensors + actuation • Reliability/testing

## Overview
Built a closed-loop watering system that reads soil moisture and opens/closes solenoid valves to regulate water flow automatically.

## Requirements
- Detect soil moisture and trigger watering when below a threshold
- Control solenoid valves reliably (repeatable open/close)
- Run unattended for extended periods

## System Architecture
**Soil moisture sensor → Raspberry Pi (GPIO logic) → Solenoid valves → Water flow**

## Implementation Notes
- Threshold-based control logic to decide when to open/close valves
- Integrated sensing + actuation hardware and validated end-to-end in real-world use

## Testing & Validation
- Tested dry vs. wet soil behavior
- Adjusted thresholds for stable behavior and reduced false triggering

## Next Improvements
- Add logging (moisture readings + valve events)
- Add fail-safe defaults (valves closed on error)
- Add enclosure/cable management for durability
