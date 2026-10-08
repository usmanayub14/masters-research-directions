# References

Checked on **30 September 2026**. For each entry, *Access* records what was actually read, so no one mistakes a citation for a reading. The IDs (R1, R2, …) match the preparation documents D1–D5.

**Access levels**
- **Full text** — the whole text was read.
- **Partial** — the named sections were read.
- **Abstract** — only the abstract or summary was read.
- **Metadata** — title, venue and identifiers were confirmed; no text was read.

## Core papers

| ID | Citation | Link | Access |
|---|---|---|---|
| R1 | N. Allison, B. Tan. SVQL: SystemVerilog Query Language. *Proc. Great Lakes Symposium on VLSI (GLSVLSI '26)*, Canandaigua, NY, pp. 311–316, June 2026. | https://doi.org/10.1145/3787109.3815250 | Partial: abstract, §3.2, §3.3, §4.1, Table 1 and §4.3, from the ACM full-text page as indexed by search (direct retrieval was blocked). Figures and full §4.2 not seen. |
| R2 | SVQL source repository (Rust). | https://github.com/nickrallison/svql | `README.md` and `TODO.md` read. May describe a newer version than the paper. |
| R3 | B. Ahmad, S. Thakur, B. Tan, R. Karri, H. Pearce. On Hardware Security Bug Code Fixes by Prompting Large Language Models. *IEEE Transactions on Information Forensics and Security*, vol. 19, pp. 4043–4057, 2024. | https://doi.org/10.1109/TIFS.2024.3374558 | Abstract (reports 15 benchmarks) |
| R4 | B. Ahmad, S. Thakur, B. Tan, R. Karri, H. Pearce. Fixing Hardware Security Bugs with Large Language Models. arXiv:2302.01215, February 2023. Preprint of R3. | https://arxiv.org/abs/2302.01215 | Full text (reports 10 benchmarks) |

## Tan group context

| ID | Citation | Link | Access |
|---|---|---|---|
| R5 | B. Tan. The Quest to Build Trust Earlier in Digital Design. arXiv:2409.05832, 2024. | https://arxiv.org/abs/2409.05832 | Full text |
| R6 | J. Ah-kiow, B. Tan. An Investigation of Hardware Security Bug Characteristics in Open-Source Projects. arXiv:2402.00684, 2024. | https://arxiv.org/abs/2402.00684 | Abstract |
| R7 | B. Ahmad, W.-K. Liu, L. Collini, H. Pearce, J. M. Fung, J. Valamehr, M. Bidmeshki, P. Sapiecha, S. Brown, K. Chakrabarty, R. Karri, B. Tan. Don't CWEAT It: Toward CWE Analysis Techniques in Early Stages of Hardware Design. *Proc. ICCAD '22*, 2022. | https://doi.org/10.1145/3508352.3549369 | Abstract (author list from R4's reference list) |
| R8 | B. Ahmad, H. Pearce, R. Karri, B. Tan. LASHED: LLMs And Static Hardware Analysis for Early Detection of RTL Bugs. arXiv:2504.21770, 2025. | https://arxiv.org/abs/2504.21770 | Abstract |
| R9 | R. Kande, H. Pearce, B. Tan, B. Dolan-Gavitt, S. Thakur, R. Karri, J. Rajendran. (Security) Assertions by Large Language Models. *IEEE TIFS*, vol. 19, pp. 4374–4389, 2024. Preprint arXiv:2306.14027. | https://doi.org/10.1109/TIFS.2024.3372809 | Metadata |
| R14 | CalgaryISH lab website (Research, Lab, PI and Opportunities pages). | https://calgaryish.com (source: https://github.com/CalgaryISH/CalgaryISH.github.io) | Pages read from the public source repository |

## Related work (not analysed)

| ID | Citation | Link | Access |
|---|---|---|---|
| R10 | H. Ahmad, Y. Huang, W. Weimer. CirFix: Automatically Repairing Defects in Hardware Design Code. *Proc. ASPLOS '22*, pp. 990–1003, 2022. | https://doi.org/10.1145/3503222.3507763 | Metadata (via R4) |
| R11 | K. Laeufer et al. RTL-Repair: Fast Symbolic Repair of Hardware Design Code. *Proc. ASPLOS '24*, pp. 867–881, 2024. | https://doi.org/10.1145/3620666.3651346 | Metadata (via R5) |
| R17 | F. Solt, B. Gras, K. Razavi. CellIFT: Leveraging Cells for Scalable and Precise Dynamic Information Flow Tracking in RTL. *USENIX Security 2022*. | — | Citation only |
| R18 | A. Ardeshiricham, W. Hu, J. Marxen, R. Kastner. Register Transfer Level Information Flow Tracking for Provably Secure Hardware Design. *DATE 2017*, pp. 1691–1696. | https://doi.org/10.23919/DATE.2017.7927266 | Metadata (via R4) |
| R20 | H. Pearce, B. Tan, B. Ahmad, R. Karri, B. Dolan-Gavitt. Examining Zero-Shot Vulnerability Repair with Large Language Models. *IEEE Symposium on Security and Privacy*, pp. 2339–2356, 2023. | https://doi.org/10.1109/SP46215.2023.10179324 | Metadata |

## Designs, standards and venues

| ID | Item | Link | Access |
|---|---|---|---|
| R12 | MITRE, CWE-1194: Hardware Design (view) | https://cwe.mitre.org/data/definitions/1194.html | Referenced; check individual CWE titles on the site before quoting them |
| R13 | lowRISC Ibex RISC-V core | https://github.com/lowRISC/ibex | `rtl/ibex_pmp.sv` module header read |
| R15 | HummingbirdV2 E203 core and SoC (Nuclei System Technology) | https://github.com/riscv-mcu/e203_hbirdv2 | Repository page |
| R16 | Hack@DAC 2018 and 2021 SoCs | https://github.com/HACK-EVENT/hackatdac18 · https://github.com/HACK-EVENT/hackatdac21 | Cited by other papers; not opened |
| R19 | GLSVLSI 2026 technical program (SVQL listed in the Hardware Security track) | https://www.glsvlsi.org/program.html | Listing |

## Known open items

- **R1:** what Table 1's "Memory (MB)" measures; the §4.2 scenario definitions; whether front-end cost or match precision is reported.
- **R2:** what the README's memory column measures.
- **R3:** the journal version's additional benchmarks and models.
