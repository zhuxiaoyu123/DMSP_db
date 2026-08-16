# DMSP Database

The updated database is in [DMSP_database](https://github.com/zhuxiaoyu123/DMSP-database).

## Annotation Method

Amino acid sequences of experimentally validated enzymes involved in DMSP, DMS, and MeSH metabolism were collected and used to construct Hidden Markov Model (HMM) profiles. These profiles were applied using **hmmsearch** to identify homologous sequences (E-value < 1 × 10⁻³⁰).

- **MegL homologues** were further analyzed using [BlastKOALA](https://www.kegg.jp/blastkoala/), and only sequences assigned to **KEGG Orthology K01761** were retained.

- Homologues of other genes were subjected to additional **DIAMOND BLASTP** analysis. Only hits with:
  - ≥40% amino acid identity, and  
  - ≥70% sequence coverage  
  relative to the reference sequences were retained.

- For **DmdA, DddD, DddK, DddP, DsyB, MddH, and TpMMT**, sequences from known non-functional homologues were included as negative references during the DIAMOND BLASTP filtering process.
