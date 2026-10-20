# booth-multiplier-4x4
Circuit-level design and simulation of a 4×4 Booth-encoded multiplier using Cadence Virtuoso.

High-Speed Booth Encoded Multiplier

A 4×4 Booth multiplier implemented using Cadence Virtuoso, exploring circuit-level design approaches for binary multiplication.

Overview

Multiplication is a fundamental operation in digital systems and is widely used in digital signal processing (DSP), arithmetic logic units (ALUs), and other hardware applications. The efficiency of a multiplier can influence the overall performance of a digital system.

This project focuses on the design of a 4×4 Booth-encoded multiplier using Cadence Virtuoso. Booth multiplication uses recoding techniques to represent multiplication operations with fewer arithmetic steps in suitable cases, particularly when handling runs of consecutive 1s in the multiplier.

The project explores the circuit-level implementation of binary multiplication and the design considerations involved in building arithmetic hardware.

Objectives

- Understand the working principle of Booth multiplication.
- Explore Booth encoding and partial-product generation.
- Implement a 4×4 multiplier using Cadence Virtuoso.
- Study the circuit-level realization of arithmetic operations.
- Understand the trade-offs involved in digital multiplier design.

Design Methodology

1. Booth Encoding

Booth's algorithm recodes the multiplier bits to determine whether each partial product requires addition, subtraction, or no arithmetic operation, together with the appropriate shifts.

2. Partial-Product Generation

The recoded multiplier information is used to generate the corresponding partial products.

3. Arithmetic Computation

The partial products are combined using arithmetic circuitry to obtain the multiplication result.

4. Circuit-Level Implementation

The multiplier was implemented in Cadence Virtuoso, providing an opportunity to explore the circuit-level realization of digital arithmetic.

Tools and Technologies

- EDA Tool: Cadence Virtuoso
- Domain: VLSI Design and Digital Circuit Design
- Core Concepts: Booth Encoding, Binary Multiplication, Partial-Product Generation, Arithmetic Circuits

Project Documentation

The repository is intended to document the design through the following materials:

- Circuit schematics
- Simulation setup and waveforms
- Input and output examples
- Design methodology and observations

Only completed and verified artifacts should be included.

Future Scope

- Compare the Booth multiplier with an alternative multiplier architecture.
- Evaluate power consumption, propagation delay, and circuit area.
- Explore design optimization at the circuit level.
- Investigate the impact of different semiconductor technologies on multiplier implementation.

Learning Outcomes

- Understanding the principles of Booth-encoded multiplication.
- Familiarity with Cadence Virtuoso for circuit-level design.
- Exposure to arithmetic circuit implementation and VLSI design concepts.







Prarthana J Mohan

Electronics and Communication Engineering

Areas of Interest: VLSI Design, Digital Circuits, Semiconductor Design

---

Note: Quantitative performance comparisons and simulation results will be added only when supported by verified design data.
