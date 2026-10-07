# Finite cardinal bases in the OpenAI partition-principle model

**Version 0.1 — preliminary research note, 7 October 2026.**

[Read the paper (PDF)](Finite_cardinal_bases_v0_1.pdf) · [LaTeX source](Finite_cardinal_bases_v0_1.tex)

This note extracts a finite coinitial basis property for the injection order on cardinalities from the stronger structural hypotheses of OpenAI’s partition-principle model. The consequences include NDS (no infinite strictly decreasing sequence of cardinalities) and the absence of infinite set-sized cardinal antichains, in the same model in which the axiom of choice fails.

## Contribution and dependencies

The model construction and the resolution of the partition-principle problem belong to **OpenAI**, in *The Partition Principle does not imply Choice*. This note proves an abstract finite-basis implication from the homogeneous-image hypotheses and applies it to the cited construction. It also records further cardinal-order consequences and open research questions.

The source is pinned to [OpenAI/math commit adc7f1241b42e322a6451854ab7e4b4c146bf78a](https://github.com/openai/math/tree/adc7f1241b42e322a6451854ab7e4b4c146bf78a). See the [source manuscript](https://github.com/openai/math/blob/adc7f1241b42e322a6451854ab7e4b4c146bf78a/preprints/The-Partition-Principle-does-not-imply-Choice-September-24-2026/partition-principle-without-choice.pdf). No third-party manuscript or Lean source is redistributed here.

The note does **not** prove the unrestricted implications PP ⇒ NDS or PP ⇒ FB, and it does not claim an independently constructed model. The historical references and exact dependencies appear in the paper.

## Status and attribution

This is a preliminary draft for review, not a peer-reviewed publication. It was prepared with substantial OpenAI Codex assistance in proof development, checking, literature searches, and drafting. The new deductions are not Lean-formalized. A bounded search completed on 7 October 2026 found no earlier publication of the central application; this is not a certification of worldwide priority or novelty.

Author: **Frederico Cançado** ([@frederico-cancado](https://github.com/frederico-cancado)). No DOI is assigned. For a fixed version, cite the author, paper title, version, and the specific release or commit URL.

## Supporting records

- [Literature search](LITERATURE_SEARCH_2026-10-07.txt): dated search scope and limitations.
- [OpenAI source audit](OPENAI_SOURCE_AUDIT_2026-10-07.txt): pinned source and attribution checks.
- [Mathematical review](MATHEMATICAL_REVIEW_2026-10-07.txt): separate AI-assisted proof audit, not human peer review.
- [Document check](DOCUMENT_CHECK.txt): compilation and visual inspection record.
- [Version history](VERSION_HISTORY.txt) and [file checksums](SHA256SUMS.txt).

Some audit records refer to retained local working files that are not distributed in this repository. The paper itself contains the arguments and bibliography.

## Rebuilding

Compile the LaTeX source twice with pdfLaTeX to resolve references. It uses standard mathematics and document-layout packages.

## License

Except where otherwise stated, the original material in this repository, including the paper PDF, its LaTeX source, and research notes, is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/), to the extent the contributor holds rights in it. See [LICENSE](LICENSE) for the full terms.

For attribution, credit **Frederico Cançado** (GitHub: **frederico-cancado**), identify the paper title and version, and link to [this repository](https://github.com/frederico-cancado/AC-zoo-results). Include a license link and indicate changes, as required by CC BY 4.0. This permits sharing and adaptation, including commercial reuse, under those terms.

Third-party material retains its own terms. This license concerns protected expression; it does not assert exclusive rights over mathematical ideas or results. The attribution to OpenAI's model construction and the AI-assistance disclosure above remain applicable.
