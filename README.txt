
----------------------
Contents of this file
----------------------

* Introduction
* 
*

----------------------
Introduction
----------------------

SEG was used to calculate the low complexity region. A customized software was used for postprocessing. 


----------------------
Software Requirements
----------------------
The customize program is writen in java. Require JRE 1.6 or better to run.

----------------------
To Execute
----------------------
sh step1_capture_seg_region.sh
sh step2_seg_postprocessing.sh

----------------------
Input Files
----------------------
homo_sapien_sp.fasta: human proteome fasta file downloaded from UNIPROT.
protein_metadata.txt: protein annotation "GR_ONLY", "PR_ONLY", "GRPR_Overlap",
"Human_Proteome".
HUMAN_ID_Table_ALL.txt: genename and protein accession.

----------------------
Output Files
----------------------
homo_sapien_low_complexity_analaysis.txt: SEG output low complexity fasta
file.
Protein_LCR.fasta: SEG output low complexity fasta file with genename.
GeneLCDLength.txt: Each protein and its LCR length.
