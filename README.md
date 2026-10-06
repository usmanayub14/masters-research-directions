# Masters Research Directions

This repository tracks my exploration of potential graduate research directions in digital hardware, with an emphasis on areas that connect naturally to my background in RTL design verification and hardware-oriented projects.

The goal is to build enough technical depth to evaluate possible MS/PhD directions, understand recent research, and identify concrete problems that are worth pursuing further.

## Current Research Threads

### 1. Automated RTL Security Detection and Repair

This thread focuses on hardware security at the RTL and netlist level, particularly:

- Hardware CWEs and security weaknesses
- Static analysis of RTL and synthesized netlists
- Structural vulnerability detection
- AST-based and graph-based analysis
- SVQL and query-based hardware security analysis
- LLM-assisted hardware security bug repair
- Verification of generated patches
- Security oracles, testbench adequacy, and validation cost
- Possible use of dependency-aware scoping for detection and re-validation

A central question I am exploring is whether security analysis and patch validation can be restricted to the logic affected by a design change without losing important findings.

See: **Issue #1 — Automated RTL Security Detection and Repair**

---

### 2. Efficient AI Acceleration for Edge Systems

This thread focuses on hardware/software co-design for efficient AI inference, especially for resource-constrained systems.

Topics of interest include:

- INT8 and low-precision inference
- Post-training quantization
- Accelerator architecture
- MAC arrays and compute organization
- Dataflow choices
- Memory hierarchy and data movement
- FPGA and ASIC implementation trade-offs
- Hardware-aware neural network optimization
- Latency, energy, memory footprint, and utilization
- Hardware/software co-design for edge AI

This direction builds on my previous work around quantized TinyML models and extends it toward the hardware architecture required to make low-precision inference efficient in practice.

See: **Issue #2 — Efficient AI Acceleration for Edge Systems**

---

## How I Am Using This Repository

The repository is intended as a research notebook rather than a finished research project.

I use the issue threads to record:

- Papers and technical material I read
- What I understand from them
- Concepts that were new to me
- Limitations of existing approaches
- Connections to my previous work
- Open technical questions
- Possible thesis directions

The emphasis is on developing and refining research questions rather than collecting large amounts of documentation.

## Current Status

Both directions are still being explored.

No final thesis direction has been selected, and the repository should not be interpreted as reporting completed research results.

As the reading progresses, promising questions may develop into small experiments, implementations, or more focused research proposals.

## Background

My primary background is in digital design verification, including RTL/SystemVerilog, simulation, assertions, regression workflows, and verification infrastructure.

I am particularly interested in research problems where verification, automation, and hardware design intersect.

## References

Sources, papers, and reading status will be tracked in [`REFERENCES.md`](REFERENCES.md) as the research threads develop.