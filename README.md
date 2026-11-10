<p align="center">
  <a href="https://github.com/orgolabs"><img src="https://orgolabs.github.io/shared/brand/orgolabs-wordmark.png" alt="orgolabs — organic chemistry labs" width="300"></a>
</p>

# The Diels–Alder Reaction — an interactive, fact-checked explainer

> Part of **[orgolabs](https://github.com/orgolabs)** — interactive, fact-checked organic chemistry labs.
> **Live site:** https://orgolabs.github.io/diels-alder/

The **Diels–Alder [4+2] cycloaddition** of **cyclopentadiene** (diene) with **maleic anhydride** (dienophile) to the bicyclic **endo** adduct. It shows *how* and *why* the reaction works: real 3D structures (PubChem + [3Dmol.js](https://3dmol.csb.pitt.edu/)), the concerted mechanism and the **endo rule**, the frontier-orbital picture, the microscale procedure, and a live limiting-reagent yield calculator.

## The chemistry in one line

A conjugated s-cis diene and an electron-poor dienophile form **two new C–C bonds** in one concerted step:
`C₅H₆ + C₄H₂O₃ → C₉H₈O₃` (cis-5-norbornene-*endo*-2,3-dicarboxylic anhydride). Endo is the kinetic major product (secondary orbital interactions).

## Run it locally

Open `index.html`, or serve with `python3 -m http.server`. The shared engine, styles, and 2D pathway images load from https://orgolabs.github.io/shared/.

## Credits & licensing

- Site content and code: **MIT License**.
- Molecular data: **PubChem**, U.S. National Library of Medicine — **public domain** (cyclopentadiene CID 7612, maleic anhydride CID 7923, endo adduct CID 2723766).
- 3D rendering: **3Dmol.js** (Rego & Koes, *Bioinformatics* 2015) — **BSD-3-Clause**.

> Educational summary only — not a substitute for a supervised laboratory SOP.
