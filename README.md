# intragenic_drop-off
Scripts for the drop-off probability estimation analysis in the article : FACT maintains chromatin architecture and thereby stimulates RNA polymerase II pausing during transcription in vivo

DOI : https://doi.org/10.1016/j.molcel.2024.05.003

The scripts performs the following operations with the bam files as input.

1. generate transcribed bases RLE tracks (filled up fragments from aligned read pairs)
2. generate coverages for the beginnings and gene body regions of the gene (TSS to TSS+3kb and TSS+3kb to TES respectively)
3. estimate the dropoff rate from the above coverages
4. generate figure 3I in the paper (using ggplot2)
