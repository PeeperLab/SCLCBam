# SCLCBam

This experiment package contains data to run the CopywriteR vignette code. The
.bam file contains sequence reads from a mouse whole-exome sequening effort on a
murine small-cell lung tumor. Only sequence reads mapping to chromosome 4 are
present in this package. The complete dataset can be downloaded from the
European Nucleotide Archive using the accession number PRJEB6954 using sample
accession number
[SAMEA2697779](http://www.ebi.ac.uk/ena/data/view/SAMEA2697779).

The package contains the accessor function getPathBamFolder() which returns the
full path to the folder containing the .bam-file.