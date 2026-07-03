# Blood Sample Handling Monitor

This project is an early prototype for a tube-mounted attachment that monitors blood sample handling conditions using motion and temperature data.

The idea is to track whether a blood tube experiences conditions that may increase the risk of sample damage, including excessive shaking, impact, prolonged agitation, or temperature exposure outside a desired range. Instead of detecting hemolysis directly through optical sensing, this system focuses on monitoring the handling conditions that can contribute to hemolysis risk.

This is not a diagnostic device. It is a prototype project meant to demonstrate biomedical device development, sensor data collection, embedded systems, requirements documentation, risk analysis, and verification planning.

## Current Status

The first hardware check is complete.

- Arduino Nano 33 connected successfully
- Test sketch uploaded through Arduino IDE
- Serial Monitor communication confirmed
- Analog input reading from pin A0 confirmed
- Initial project documentation started

## Project Goal

Build a small proof-of-concept system that can:

1. Attach to or remain with a blood sample tube during handling
2. Record motion/agitation data
3. Record temperature data
4. Flag handling events that may increase hemolysis risk
5. Store readings in a structured format
6. Document the design using requirements, traceability, V&V planning, and FMEA

## Project Reasoning

Hemolysis can occur when blood samples are exposed to poor handling conditions such as excessive shaking, impact, or unsuitable storage temperatures. In clinical and laboratory workflows, it can be useful to know whether a sample experienced risky handling before testing.

This project is focused on the engineering workflow behind a sample handling monitor:

- embedded sensor reading
- motion and temperature data logging
- threshold-based event detection
- sample quality risk scoring
- design controls
- verification planning
- risk analysis

