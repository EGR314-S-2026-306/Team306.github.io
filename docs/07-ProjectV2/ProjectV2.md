---
title: ProjectV2
---


## Version 2.0 Overview
Version 2.0 of the rover would focus on improving reliability, adding more sensing capability, and making the system easier to test and debug. The first version worked well for demonstrating communication between subsystems, but it also showed limits in hardware layout, message handling, and system integration. A second version would refine the electrical design, improve subsystem interfaces, and strengthen the communication protocol so the rover can support more advanced functions.

## New Functions and Capabilities
A major upgrade in Version 2.0 would be expanding the rover’s sensing abilities. The current design focuses on magnetic field detection and drilling feedback. A new version could add temperature, humidity, or soil conductivity sensors to give a more complete picture of the underground environment. Adding a small onboard display or LED status panel would also help operators by giving immediate feedback without relying only on wireless communication. These additions would require updates to the block diagram and protocol but would make the rover more useful and informative.

## Improving Debuggability
Debugging the first version required a lot of manual probing and serial monitoring. Version 2.0 would add dedicated test points on each subsystem’s PCB so power rails, communication lines, and sensor outputs can be checked quickly. Each subsystem would also include a standard debug UART port for monitoring internal state without interfering with wireless communication. A simple logging system could be added so each subsystem reports status, error codes, and sensor readings at regular intervals. These changes would make testing faster and help catch issues earlier.

## Hardware Reliability and Stability
Version 2.0 would improve the rover’s electrical and mechanical reliability. The power system would be redesigned with better filtering, stronger voltage regulation, and protection parts like TVS diodes and resettable fuses. These changes would protect the rover from electrical noise caused by motors and drilling. The wireless subsystem would benefit from better antenna placement and shielding. Mechanically, the frame could be reinforced to reduce vibration, which would help sensor accuracy and extend the life of the drill.

## Protocol and Software Updates
The communication protocol would be updated to support new features. The current 64‑byte packet format works, but Version 2.0 would simplify it by removing unused fields and adding optional extensions. A checksum or CRC would improve error detection. Message types could be reorganized so related commands share a common structure, making the protocol easier to understand and expand.

The software architecture would also become more modular. In Version 1.0, each subsystem handled message parsing differently. Version 2.0 would use a shared library for encoding, decoding, and validating messages. A state‑machine approach would make subsystem behavior more predictable and easier to debug by clearly defining states, transitions, and error handling.

## Summary
Version 2.0 would expand sensing, improve reliability, simplify debugging, and strengthen the communication protocol. These changes would make the rover more robust and better suited for real exploration tasks. The updated design would build on the strengths of the original project while addressing the issues discovered during development and testing.