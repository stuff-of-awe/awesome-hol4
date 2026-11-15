<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# Awesome HOL4

Learn interactive higher-order logic with theories, tactics and reusable libraries.

## Start here

- [HOL4 project](https://hol-theorem-prover.org/) — Follow the installation and community links for the release you use.
- [Manuals and reference](https://hol-theorem-prover.org/docs/latest/) — Start with the tutorial, then consult the reference for a tactic or theory.
- [Source repository](https://github.com/HOL-Theorem-Prover/HOL) — Browse examples and library theories alongside the build instructions.

## First investigation

Create a small theory following the official tutorial and locate one theorem it imports. Record the HOL4 release and ML runtime.

This is a suggested learning exercise. It has not been execution-tested by this collection.

## Contribute and maintain

Starter collection reviewed 3 November 2026. Volunteer curators welcome. Suggest a resource or correction through this repository's issues or pull requests. Include its canonical URL, intended audience, version requirements and any affiliation.

The initial GitHub name search found no dedicated awesome list for this tool. The search is preliminary. Please suggest relevant upstream collections. All annotations here are newly written. Linked projects retain their own authorship and licences.

[Collection policy](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/MAINTENANCE.adoc) · [Community guidance](https://github.com/stuff-of-awe/.github/blob/main/CONTRIBUTING.md)

## A verified prover built using HOL4

- [Candle](https://cakeml.org/candle/) — An implementation of HOL Light on CakeML whose end-to-end machine-code soundness theorem was established in HOL4. Explore its theorem-export channel, the proof assumptions and the certified compiler boundary before citing this as a whole-system guarantee.
- [Candle source](https://github.com/CakeML/candle) — Source and setup materials for studying the verified prover, rather than assuming it is another HOL4 binary.
- [CakeML verified proof checkers](https://www.cakeml.org/checkers.html) — Related work on certified certificate checking for SAT and other proof outputs; different deliverable and trust boundary from interactive HOL provers.

These links were reviewed 15 November 2026, but no local Candle build or proof check was performed. HOL4 is a verification tool for Candle; Candle should not be described as a feature of the ordinary HOL4 executable.
