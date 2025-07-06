# MD Simulation: Alpha-Synuclein with N/B-Doped Graphene

This project simulates the interaction between alpha-synuclein protein and nitrogen/boron co-doped graphene using GROMACS. The study aims to understand how doped graphene surfaces can affect the structural dynamics of proteins involved in neurodegenerative diseases such as Parkinson’s.

## Methods

- **Software:** GROMACS 2022
- **Protein:** Chain A of alpha-synuclein (PDB ID from RCSB)
- **Graphene:** Graphene sheet with 25% random substitution of carbon by nitrogen and boron
- **Force fields:**
  - OPLS-AA/L for protein
  - CHARMM36 for doped graphene
- **Simulation:** Energy minimization → NVT → NPT → 1 ns production run

## Results

- **RMSD**: Protein reached ~2 nm after 1 ns, showing stable interaction with graphene
- **Radius of Gyration (Rg)**: Decreased from 3.7 nm to 3.3 nm indicating structural compaction
- Graphene showed potential to affect the folding and aggregation behavior of alpha-synuclein

## Visualization

- Snapshots generated using VMD and PyMOL
- Plots for RMSD and Rg included in `results/`

## Author

Phạm Thị Tường Vân – Final-year Materials Science student, VNU-HCM University of Science

## Reference

The full project report is available in `/report/Final_Report_TuongVan.pdf`.

---
