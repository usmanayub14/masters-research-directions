# Hardware Security Research

This repository tracks my learning and research exploration around **hardware security at RTL**, with a focus on automated vulnerability detection, static analysis, and security bug repair.

My background is primarily in digital design verification, so I am approaching hardware security from the verification side: understanding how security weaknesses appear in RTL, how they can be detected automatically, and how generated fixes can be validated reliably.

## Current Focus

I am currently studying:

- Hardware security fundamentals and hardware CWEs
- RTL and netlist-based static analysis
- Structural vulnerability detection
- SVQL and query-based hardware security analysis
- LLM-assisted hardware security bug repair
- Verification of generated patches and the strength of test/security oracles

Two questions I am particularly interested in are:

1. Can hardware security analysis be scoped around the logic affected by a design change without losing important cross-module findings?
2. Can dependency-aware test or check selection reduce the cost of validating automatically generated RTL fixes without allowing incorrect or insecure patches to pass?

## Repository Structure

```text
.
├── README.md
├── REFERENCES.md
├── notes/
│   ├── hardware-security-fundamentals.md
│   └── rtl-static-analysis.md
├── papers/
│   ├── svql.md
│   └── llm-hardware-bug-repair.md
└── research/
    └── research-directions.md
```

The repository will grow as I read, verify ideas against the original papers, and develop my own observations.

## Current Reading

My current reading includes:

- N. Allison and B. Tan, **SVQL: SystemVerilog Query Language**, GLSVLSI 2026.
- B. Ahmad, S. Thakur, B. Tan, R. Karri and H. Pearce, **On Hardware Security Bug Code Fixes by Prompting Large Language Models**, IEEE TIFS 2024.
- Related work on hardware CWEs, static analysis, LLM-assisted detection, and automated RTL repair.

The complete reference list and what I have actually read from each source are tracked in [`REFERENCES.md`](REFERENCES.md).

## Status

This repository currently contains **learning notes and research questions, not research results**.

Any implementation, experiments, measurements or conclusions will be added only after they have actually been performed and verified.