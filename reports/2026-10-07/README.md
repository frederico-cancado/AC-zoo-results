# Complete research results — 7 October 2026

**Frederico Cançado · Preliminary version 2026-10-07.1**

[Read the complete report](Complete_research_results.pdf) · [LaTeX source](Complete_research_results.tex) · [Source and proof archive](complete-research-source-and-evidence.zip)

This report consolidates the research results obtained so far: the finite-basis/NDS/cardinal-antichain consequences of OpenAI's PP model; the native order-extension and BPI obstruction; Boolean and graph compactness witnesses; cardinal order and exponentiation; parameter and Ramsey spectra; the finite-order forcing extension and its unresolved global choice principles; and the earlier ordinary-FM criteria and counterexamples.

The source construction is due to OpenAI, at pinned commit `adc7f1241b42e322a6451854ab7e4b4c146bf78a`. The report distinguishes source theorems, additional audited deductions, conditional statements and open questions. It does **not** prove PP implies NDS in arbitrary ZF models. It does **not** establish PP or BPI in the new finite-order extension.

The report includes substantial proof arguments and sketches. The archive contains all LaTeX sections and the retained supporting mathematical notes, source-verification records, two auxiliary Lean developments and dated literature audits. `SOURCE_MAP.tsv` identifies the original working-file sources and checksums. Earlier chronological notes are read subject to the current report's statuses. The imported conversation and third-party construction sources are not redistributed.

The work was developed and checked with substantial OpenAI Codex assistance. Separate AI mathematical audits are not independent human peer review. The original construction was locally compiled in Lean; the scope of that check and of the much smaller new Lean checks is described precisely in the report. Most new deductions are not Lean-formalized. Novelty is based on bounded searches, not certified priority.

Compile `Complete_research_results.tex` with pdfLaTeX three times from this directory. Standard TeX Live packages are listed in the preamble. `DOCUMENT_CHECK.txt` records final compilation and visual checks. No DOI is asserted. For a fixed citation, use this version and the exact GitHub commit.

Original expression is licensed under CC BY 4.0 to the extent the contributor holds rights in it; see `LICENSE`. Credit Frederico Cançado, retain the OpenAI construction attribution, and disclose substantive changes.
