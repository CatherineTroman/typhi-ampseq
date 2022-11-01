# typhi-ampseq
Documents and files for genotype analysis using data produced by MinION sequencing of S.Typhi amplicons.

# Installation

You will need to follow installation instructions and environment set up for RAMPART (Artic Network) on the github ages here:
https://github.com/artic-network/rampart 

You also need to make sure samtools and bcftools are installed in that environment and that the versions match eachother.
These can be installed using the following commands:

conda install -c bioconda samtools
conda install -c bioconda bcftools

Clone this repository to get the documents for the genotyphi analysis. The genotyphi_ampseq.py file is adapted from
https://github.com/peterk87/genotyphi.git which was forked from the orginal genotyphi repository (https://github.com/katholt/genotyphi)

# Running the analysis

