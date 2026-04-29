# DMSP Database

## Enzymes Involved in DMSP, DMS, and MeSH Metabolism

<img width="863" height="586" alt="image" src="https://github.com/user-attachments/assets/821465d2-9b40-440f-8622-ee58867f32b6" />

- **BurB** is a key enzyme in the methylation pathway of DMSP biosynthesis. In *Burkholderia thailandensis*, it contributes to the production of DMSP, which serves as a precursor for virulence-associated compounds.

<br>

<img width="1050" height="1256" alt="image" src="https://github.com/user-attachments/assets/3aadf3c7-0c31-403c-b4b9-c0774ce06ad2" />

- **AcuH** is also known as **AcuK**.

---

## Annotation Method

Amino acid sequences of experimentally validated enzymes involved in DMSP, DMS, and MeSH metabolism were collected and used to construct Hidden Markov Model (HMM) profiles. These profiles were applied using **hmmsearch** to identify homologous sequences (E-value < 1 × 10⁻³⁰).

- **MegL homologues** were further analyzed using [BlastKOALA](https://www.kegg.jp/blastkoala/), and only sequences assigned to **KEGG Orthology K01761** were retained.

- Homologues of other genes were subjected to additional **DIAMOND BLASTP** analysis. Only hits with:
  - ≥40% amino acid identity, and  
  - ≥70% sequence coverage  
  relative to the reference sequences were retained.

- For **DmdA, DddD, DddK, DddP, DsyB, MddH, and TpMMT**, sequences from known non-functional homologues were included as negative references during the DIAMOND BLASTP filtering process.
