This repository contains supplementary materials for the long-read sequencing variant calling pipeline guide.

**Pre-alignment QC**:
To see an example of the FastQC .html report of a real HiFi sequencing raw BAM file, download the following file 
and open in your web browser of choice (recommended Safari or Firefox). [Example_of_Real_Sequencing_Sample.html](https://github.com/user-attachments/files/29051802/Example_of_Real_Sequencing_Sample.html)

After compiling multiple fastQC outputs with multiQC, a single .html report will be generated with all of the summary
statistics across each sample. To see an example of the multiQC .html report, download the following file and simiarly
open in a web browser. [Example_of_Real_Multisample_MultiQC.html](https://github.com/user-attachments/files/29052039/Example_of_Real_Multisample_MultiQC.html)

**Post-alignment QC**:
After compiling samtools stats .txt output files with multiQC, a single .html report will simiarly be generated. An example of this 
report can be seen by downloading the following file and opening in a web browser. [Example_of_Real_samtools_stats_MultiQC.html) [https://github.com/jbutle67/LRS_Pipeline_Guide/blob/11c42d391299c330aa8ce108b11c5e3521d274d1/Example_of_Real_samtools_stats_MultiQC.html]
