# USENIX-26-Johnny-Usability-Study
# Why Johnny Adopts Identity-Based Software Signing: A Usability Case Study of Sigstore
This is the repository for artifacts described in the paper "*Why Johnny Adopts Identity-Based Software Signing: A Usability Case Study of Sigstore*" by K.G. Kalu, S. Okorafor, T. Singla, S. Chen, S. Torres-Arias, and J.C. Davis.

### Citation
To cite this Article or Artifact - use:

```
@inproceedings{Kalu_Johnny-usability-study_2026,
  title     = {Why Johnny Adopts Identity-Based Software Signing: A Usability Case Study of Sigstore},
  author    = {Kelechi G. Kalu and Sofia Okorafor and Tanmay Singla and Sophie Chen and Santiago Torres-Arias and James C. Davis},
  booktitle = {Proceedings of the 35th USENIX Security Symposium (USENIX Security '26)},
  year      = {2026},
  address   = {Baltimore, MD, USA},
  publisher = {USENIX Association}
}
```

## Table of Contents

- [Why Johnny Adopts Identity-Based Software Signing: A Usability Case Study of Sigstore](#why-johnny-adopts-identity-based-software-signing-a-usability-case-study-of-sigstore)
  - [Table of Contents](#table-of-contents)
- [CODEBOOK](#codebook)
  - [Codebook](#codebook-1)
  - [Evolution of Codebook Tooling](#evolution-of-codebook-tooling)
  - [Evolution of Codebook ALL](#evolution-of-codebook-all)
  - [Rater A, Rater B](#rater-a-rater-b)
  - [Reliability (Rater A - Rater B)](#reliability-rater-a---rater-b)
  - [CODE PER SUBJECTS- TOOLING](#code-per-subjects--tooling)
  - [Code Saturation- (Tooling)](#code-saturation--tooling)
  - [Code Saturation - ALL](#code-saturation---all)
  - [Tooling Study Theme Definition](#tooling-study-theme-definition)
  - [Driver (Push-Pull-Barrier) Map](#driver-push-pull-barrier-map)
  - [Interview Protocol](#interview-protocol)
- [Technical Report](#technical-report)
  - [Summary of Appendix Items](#summary-of-appendix-items)
  - [Tables Included in the Technical Report](#tables-included-in-the-technical-report)
  - [Additional Notes](#additional-notes)


# CODEBOOK
**Filename:**  `codebook.xlsx`
This spreadsheet contains data, coding frameworks, and analysis results from our study. Below is a summary of each sheet in the workbook:

## Codebook
Contains the finalized coding scheme used in the analysis of our coded interviews. It defines each code and categorizes them under major themes such as Technological, Organizational, Human, and Macroenvironmental factors.

## Evolution of Codebook Tooling
Tracks the iterative development and refinement of the codebook specifically for the tooling (usability) study. This includes initial codes, revisions, and the rationale behind changes.

## Evolution of Codebook ALL
Similar to the tooling-specific evolution, but covers the broader study (covering Parts B & C of the Protocol) if multiple sub-studies were conducted. Shows the holistic evolution of all codes in the wider study.

## Rater A, Rater B
Contain the individual coding results from two independent raters. Each row corresponds to a participant or excerpt, with the applied codes listed for comparison.

## Reliability (Rater A - Rater B)
Summarizes inter-rater reliability statistics such as code agreement/disagreement. Useful for validating the consistency of qualitative coding between raters.

## CODE PER SUBJECTS- TOOLING
Aggregates for which codes were assigned to each subject (participant) in the tooling study. Helps in understanding the prevalence and distribution of codes.

## Code Saturation- (Tooling)
Analyzes the point at which thematic saturation was reached during the tooling interviews. Shows how many new codes emerged over successive interviews.

## Code Saturation - ALL
Same as above, but for the entire dataset across different sub-studies (not just our usability study). Indicates the completeness of thematic coverage.

## Tooling Study Theme Definition
Provides detailed definitions and explanations for each theme specific to the tooling study. Acts as a reference for interpreting the codes used.

## Driver (Push-Pull-Barrier) Map
This defines the Driver labels (Push/Pull/Barrier) mapped to concrete codes with factor tags (T/P/O/M) and example participant IDs. This is the mapping used to describe results in §5.2.3 

## Interview Protocol
This summarizes our interview protocol for the entire study, with changes made for the entire duration of the study. 

# Technical Report  
**Filename:** `Technical-Report.pdf`

This technical report is an **extended version** of our paper submitted to **USENIX Security 2026**.  
It provides additional methodological detail, expanded results, and supporting artifacts that complement the main paper but could not be included due to space constraints.

---

## Summary of Appendix Items

| Appendix | Description |
|--------|-------------|
| **Appendix A** | **Traditional Software Signing Workflow.** Detailed description of legacy key-managed signing workflows, including signing and verification phases, with an illustrative figure contrasting traditional and identity-based signing. |
| **Appendix B** | **Full Interview Protocol.** Complete semi-structured interview protocol, including demographic questions, organizational signing context, and signing tool usability questions, with annotations reflecting protocol evolution. |
| **Appendix C** | **Codebooks Excerpts.** Final codebooks used in the thematic analysis, including code definitions and representative participant quotes mapped to each code. |
| **Appendix D** | **Code Saturation Analysis.** Saturation curve and explanation showing how themes stabilized across interviews. |
| **Appendix E** | **Extended Results and Analyses.** Additional analyses omitted from the main paper due to space constraints, organized into sub-appendices: |
| **Appendix E.1** | Sigstore components most commonly used by participants. |
| **Appendix E.2** | Additional organizational and tooling effects related to identified usability concerns. |
| **Appendix E.3** | Expanded demographic tables, including organizational context. |
| **Appendix E.4** | Factors influencing Sigstore adoption among Sigstore users prior to adoption. |
| **Appendix E.5** | Factors influencing consideration or rejection of Sigstore among non-Sigstore users. |
| **Appendix E.6** | Additional discussion and implications of results beyond those presented in the main paper. |
| **Appendix F** | **Survey Results.** Raw survey results collected as a follow-on to interviews; excluded from the main paper due to data quality concerns. |

---

## Tables Included in the Technical Report

- **Subject Demographics.**  
  *Extended with interview duration*

- **Interview Protocol. Sections A–C reflect demographics, signing use/motivation context, and signing tool usability.**  
  *We analyze part C in this study and use the other themes as context.*

- **Driver labels (Push/Pull/Barrier) mapped to concrete codes with factor tags (T/P/O/M) and example participant IDs.**
- **Sigstore Functionalities Used by Subjects.**
- **Organizational Demographics. To enhance anonymity, we only highlight the number of subjects in each organizational category. Letters A-L are used to depict each organization.**
- **Reasons Practitioners Choose or Switch to Sigstore Before Adoption.**
- **Non Sigstore Users: Tooling Issues causing a consideration of Sigstore and other Next-gen tools.**

---

## Additional Notes

- The technical report emphasizes **methodological transparency**, including the full instrument, saturation analysis, and extended tables to support interpretation and replication.
- Interview transcripts and other sensitive materials are excluded to preserve participant confidentiality and comply with IRB requirements.


This extended documentation is intended to increase transparency, reproducibility, and completeness of our findings for the community.

