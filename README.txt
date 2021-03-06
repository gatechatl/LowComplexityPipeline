
----------------------
Contents of this file
----------------------

* Introduction
* Software Requirements
* Shell Executables
* Input Files
* Intermediate Files
* Output Files
* Reference

----------------------
Introduction
----------------------

SEG was used to calculate the low complexity region. A custom software was
used for postprocessing the result. 


----------------------
Software Requirements
----------------------

Program for parsing the software is written in java. Linux environment is
preferred. Require JRE 1.6 or better to run. SEG might need to be recompiled before executing the shell script. The source code of the DRPPM package could be accessed at https://github.com/gatechatl/DRPPM.


----------------------
Shell Executable 
----------------------

To execute the pipeline, please run the following shell scripts.
sh step1_capture_seg_region.sh
sh step2_seg_postprocessing.sh


----------------------
Input Files
----------------------

1. homo_sapien_sp.fasta: human proteome fasta file downloaded from UNIPROT.
2. protein_metadata.txt: protein annotation "GR_ONLY", "PR_ONLY", "GRPR_Overlap",
"Human_Proteome".
3. HUMAN_ID_Table_ALL.txt: genename and protein accession.


----------------------
Intermediate Files
----------------------

1. homo_sapien_low_complexity_analaysis.txt: SEG output low complexity fasta file.


----------------------
Output Files
----------------------

1. Protein_LCR.fasta: SEG output low complexity fasta file with genename.
2. GeneLCDLength.txt: Each protein and its LCR length.


----------------------
Reference
----------------------

Kyung-Ha Lee et al. C9orf72 dipeptide impair the assembly, dynamics and
    function of membrane-less organelles. Cell. 2016. (accepted).

* For any technical questions please contact 
    Tim Shaw tim.shaw@stjude.org

