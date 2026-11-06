# Week 1: Chemical & Biochemical Foundations

**Primary Source:** MIT 7.01SC (Unit 1: Biochemistry)  

---

## 1. Key Concepts Learned This Week
* **Covalent Bonds:** Strong electron-sharing bonds forming the backbone of biomolecules (like the phosphodiester bonds in DNA).
* **Hydrogen Bonds:** Weak electrostatic attractions between polar molecules; crucial for holding the DNA double helix together.
* **The Hydrophobic Effect:** How non-polar molecules interact in water, driving 3D protein folding.

## 2. Why This Matters for Genomics
When sequencing long reads (like Oxford Nanopore technology), separating DNA strands relies on thermal or enzymatic breaking of hydrogen bonds. Understanding $G-C$ vs $A-T$ bonding stability helps explain sequencing dynamics.

## 3. Study Checklist
- [x] Review water polarity and hydrogen bonding
- [ ] Understand the 4 major classes of biological macromolecules
- [ ] Commit notes to GitHub


```mermaid
graph TD
    A[Primary Amino Acid Sequence] -->|Hydrophobic Collapse| B[Secondary Structures]
    B -->|Hydrogen Bonding| C[Alpha Helices and Beta Sheets]
    C -->|Tertiary Folding| D[3D Functional Enzyme]
