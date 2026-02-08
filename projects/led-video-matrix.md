# Programmable Studio LED System (Music-Reactive LEDs + Video-Driven LED Matrix)

**Type:** Personal Project  
**Focus:** Hardware integration • LED control • Reliability/testing • Creative tech systems  
**Tools/Platform:** Programmable LEDs • Custom LED matrix • Studio installation • (Add controller details if you want)

## Overview
Designed and installed a programmable LED lighting system for my music studio that can (1) create motion/effects that react to music and (2) display video content on a custom LED matrix mapped from MP4 files. Built to be reliable enough for daily use and fast setup.

## Requirements (What success meant)
- Produce repeatable, programmable lighting motion/effects in a studio environment
- React to music in a way that feels responsive and visually clear
- Display video content on an LED matrix using MP4/video files
- Keep the system stable for long sessions (no random dropouts or “glitchy” behavior)
- Be cleanly mounted and integrated so it’s usable day-to-day (not a fragile prototype)

## System Architecture (High Level)
**Audio / music → analysis/control layer → LED output**
- **Inputs:** music/audio signal (for reactive effects), MP4/video files (for matrix content)
- **Control/Mapping:** effect logic + mapping from audio/video content to LED layout
- **Outputs:** studio LED strips/fixtures + custom LED matrix display

## Implementation Notes
- Designed the physical layout of LEDs in the studio for even coverage and intentional “movement”
- Built a custom LED matrix and configured pixel mapping so video content displays correctly on the physical layout
- Created programmable motion/effects for music-reactive behavior (tuned for the room and typical studio volumes)
- Focused on practical usability: clean mounting, stable connections, and repeatable startup procedure

## Testing & Validation
- Validated music-reactive responsiveness by testing across multiple playback levels and track styles
- Tested video playback mapping with different MP4 files (brightness, motion, and content readability)
- Ran extended “long session” tests to confirm stability and consistent output over time
- Iterated on effect timing and mapping to reduce visible artifacts and improve perceived smoothness

## Challenges & Fixes (Examples)
- **Content mapping:** ensuring that video content aligns correctly to the physical matrix layout  
  **Fix:** refined mapping and alignment until video motion read correctly on the installed grid
- **Consistency:** avoiding inconsistent behavior between sessions  
  **Fix:** standardized a repeatable setup/startup workflow and stabilized physical connections

## Media
(Add photos here after you upload them to `assets/img/`)
- Example: ![Studio LEDs](../assets/img/ledmatrix_01.jpg)
- Example: ![LED matrix display](../assets/img/ledmatrix_02.jpg)

## Next Improvements
- Add a simple control UI for quickly selecting modes (reactive / video / static scenes)
- Add presets designed for different use cases (recording, chill ambience, performance, etc.)
- Add logging/health indicators (power, signal, connection status) for easier troubleshooting
- Improve enclosure/cable routing for maximum durability and cleaner maintenance
