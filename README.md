# DMSP database
## Enzymes involved in DMSP, DMS and MeSH metabolism
<img width="1019" height="692" alt="image" src="https://github.com/user-attachments/assets/1e52b3d2-75eb-4c9b-8480-c3a2baef9b9b" />
<img width="1050" height="1256" alt="image" src="https://github.com/user-attachments/assets/3aadf3c7-0c31-403c-b4b9-c0774ce06ad2" />
*AcuH is also known as AcuK

Amino acid sequences of ratified enzymes involved in DMSP/DRC metabolism were used to create HMM profiles, which were then employed by hmmsearch to identify homologues (e-value < 1 × 10-30). MegL homologues were further submitted to BlastKOALA18 (https://www.kegg.jp/blastkoala/), and only sequences assigned to KEGG Orthology K01761 were considered as MegL. Homologues of other genes were subjected to a further DIAMOND BLASTP19 analysis, and only homologues with ≥40% amino acid identity and ≥70% coverage relative to ratified sequences were retained. For DmdA, DddD, DddK, DddP, DsyB, MddH, and TpMMT, sequences from non-functional homologues were included as negative references in the DIAMOND BLASTP analysis.
