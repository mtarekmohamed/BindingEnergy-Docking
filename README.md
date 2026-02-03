# Docking and Binding Free Energy Calculations

This repository contains computational workflows for **molecular docking,
binding free energy calculations, dimensionality reduction, and Markov State
Modeling (MSM)**, developed and applied across multiple structure-based
drug-discovery projects.

The methods implemented here were used in the following studies:

- **Novel allosteric effectors targeting human transcription factor TEAD**  
  *Int. J. Mol. Sci.* (2023)  
  DOI: https://doi.org/10.3390/ijms24109009

- **Homology modeling of Forkhead box protein C2: identification of potential inhibitors
  using ligand- and structure-based virtual screening**  
  *Molecular Diversity* (2022)  
  DOI: https://doi.org/10.1007/s11030-022-10519-0

- **Computational investigation of peptidomimetics as potential inhibitors of
  SARS-CoV-2 spike protein**  
  *Journal of Biomolecular Structure and Dynamics* (2023)  
  DOI: https://doi.org/10.1080/07391102.2022.2116601

---

## Scope of the Repository

This repository provides reusable, target-agnostic workflows for:

- molecular docking and virtual screening,
- binding free energy calculations,
- dimensionality reduction and state-space analysis,
- Markov State Model (MSM) construction and analysis.

The workflows are adaptable to different biological systems, including
transcription factors, viral proteins, and regulatory signaling proteins.

---

## Methods Implemented

### Molecular Docking
- Docking and virtual screening were performed using the **FRED** docking package.
- Structure-based docking was applied to experimental structures or homology models.
- Post-docking pose analysis and ranking were used to identify promising candidates.

### Binding Free Energy Calculations
- Binding free energy calculations were performed using **MM/GBSA**.
- Energies were computed from **AMBER molecular dynamics simulations**.
- Analysis was carried out using **AmberTools**.
- These calculations were used to refine docking results and rank ligands and
  peptidomimetics.

### Dimensionality Reduction
- The repository contains **multiple dimensionality reduction techniques**
  (e.g., linear and nonlinear methods) applied to simulation-derived features.
- Different approaches were evaluated to identify the most informative
  low-dimensional representations for each project.

### Markov State Modeling (MSM)
- MSM scripts are included to:
  - discretize conformational space,
  - identify metastable states,
  - analyze conformational kinetics and state populations.
- MSM analysis was used to complement docking and free energy results with
  dynamic information.

---

## Intended Use

This repository is intended for:
- structure-based drug discovery,
- docking and binding free energy analysis,
- MD-based free energy refinement,
- kinetic and state-space analysis using MSMs,
- reproducible computational chemistry workflows accompanying peer-reviewed studies.

---

## Citation

If you use the code or workflows in this repository, please cite the relevant
publication(s) listed above and the underlying software packages
(FRED, AMBER, AmberTools) as appropriate.

