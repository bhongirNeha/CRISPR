# CRISPR

TABLE OF CONTENTS

+ [Introduction](#introduction)

+ Objective

+ Background

+ Workflow

+ References

  
INTRODUCTION

Clustered regularly interspaced short palindromic repeats (CRISPR)/CRISPR-associated protein 9 (Cas9) gene-editing technology is the ideal tool of the future for treating diseases by permanently correcting deleterious base mutations or disrupting disease-causing genes with great precision and efficiency.The CRISPR/Cas9 system evolved naturally in bacteria and archaea as a defense mechanism against phage infection and plasmid transfer.



The genome editing process using CRISPR-Cas9 unfolds through several steps. Firstly, the CRISPR-Cas9 components are introduced into the target cells, commonly via viral vectors or direct injection. Within the cells, Cas9 and the gRNA form a complex that navigates the genome, seeking the target DNA sequence based on gRNA complementarity . Upon locating the target site, the Cas9 protein triggers a precise double-strand break (DSB) at that locus. DSB repair encompasses two primary pathways: non-homologous end joining (NHEJ) and homology-directed repair (HDR). NHEJ, recognized for its propensity for errors, frequently produces minor insertions or deletions (indels) at the DSB location. In contrast, HDR relies on a template DNA molecule to facilitate accurate modifications.


OBJECTIVE

The Goal is to target PTPN22 (R620W) gene responsible for Rheumatoid arthritis disease by the use of CRISPOR tool.


BACKGROUND:RHEUMATOID ARTHRITIS

Rheumatoid arthritis (RA) is a common and complex autoimmune disorder in which the immune system erroneously targets the body's own tissues, particularly affecting the joints. This condition is characterized by chronic inflammation that progressively damages synovial joints, leading to pain, swelling, and the destruction of cartilage and bone.A genetic variant particularly a SNP in the gene PTPN22 (R620W, rs2476601) is strongly associated with increased risk for multiple autoimmune diseases and linked to altered TCR regulation and T cell activation. Inparticular, the   R620W variant of   this   protein is associated   with it. This gene was taken for crispr/cas9 editing.

WORKFLOW


1.Open UCSC Genome Browser


2.Search rs2476601,Target coordinates:
rs2476601 - chr1:113834846-113835046


3.Select GRCh38 / hg38 Assembly


4.View--DNA Sequene--Get DNA--Copy 


5.https://crispor.gi.ucsc.edu/crispor.py


6.Paste the sequence---


7.Select Genome: Homo sapiens - Human - UCSC hg38


8.Select PAM :20bp-NGG (SpCas9)


9.SUBMIT


10.Result analysis based on Scores.


REFERENCES


Li, T., Yang, Y., Qi, H. et al. CRISPR/Cas9 therapeutics: progress and prospects. Sig Transduct Target Ther 8, 36 (2023). https://doi.org/10.1038/s41392-023-01309-7

Aljabali, A. A., El-Tanani, M., & Tambuwala, M. M. (2024). Principles of CRISPR-Cas9 technology: Advancements in genome editing and emerging trends in drug delivery. Journal of Drug Delivery Science and Technology, 92, 105338.


Chumi Sarma, Vivek Jyoti Das*, Rubli Sarma, Innovative Gene Therapy Approaches For Treatment Of Rheumatoid Arthritis, Int. J. of Pharm. Sci., 2024, Vol 2, Issue 10, 1843-1852. https://doi.org/10.5281/zenodo.14017689


Warren AndersonFariba Barahmand-pour-WhitmanPeter S LinsleyKaren CerosalettiJane H BucknerDavid J Rawlings (2023) PTPN22 R620W gene editing in T cells enhances low-avidity TCR responses eLife 12:e81577.
https://doi.org/10.7554/eLife.81577


Shivaraman, A., & Guilz, N. (2022). Immunotherapy using CRISPR-Cas9 systems to treat rheumatoid arthritis with PTPN22 R620W mutations and target PD-1 and CD20. Journal of High School Science, 6(1).









