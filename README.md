# DMSP database
## Enzymes involved in DMSP, DMS and MeSH metabolism
<img width="863" height="586" alt="image" src="https://github.com/user-attachments/assets/821465d2-9b40-440f-8622-ee58867f32b6" />
*BurB is a key enzyme in the methylation pathway of DMSP production, particularly in Burkholderia thailandensis, where it helps produce DMSP as a precursor to virulence factors.
<br>
<img width="1050" height="1256" alt="image" src="https://github.com/user-attachments/assets/3aadf3c7-0c31-403c-b4b9-c0774ce06ad2" />
*AcuH is also known as AcuK
<br>
## Annotation method
Amino acid sequences of ratified enzymes involved in DMSP/DMS/MeSH metabolism were used to create HMM profiles, which were then employed by hmmsearch to identify homologues (e-value < 1 × 10-30). MegL homologues were further submitted to BlastKOALA18 (https://www.kegg.jp/blastkoala/), and only sequences assigned to KEGG Orthology K01761 were considered as MegL. Homologues of other genes were subjected to a further DIAMOND BLASTP19 analysis, and only homologues with ≥40% amino acid identity and ≥70% coverage relative to ratified sequences were retained. For DmdA, DddD, DddK, DddP, DsyB, MddH, and TpMMT, sequences from non-functional homologues were included as negative references in the DIAMOND BLASTP analysis.
