Contig properties in addition to basic statistics:
 - `x`, `y`: Coordinates based on *k*-mer signature, as determined by [VizBin](http://claczny.github.io/VizBin/).
 - `reads`: Number of reads mapped to this contig.
 - `orfs`: Number of ORFs prediced by [Prodigal](https://github.com/hyattpd/Prodigal).
 - `ssus`: Number of SSUs predicted by [Metaxa2](http://microbiology.se/software/metaxa2/).
 - `concoct`, `maxin`, `metabat`: Bin IDs assigned by [CONCOCT](https://github.com/BinPro/CONCOCT), [MaxBin](https://sourceforge.net/projects/maxbin/) and [MetaBat](https://bitbucket.org/berkeleylab/metabat), respectively.
 - `classified`: Number of reads with taxonomic assignment.
 - `toptax`: ID of taxon with most reads assigned to.
 - `ntop`: Number of reads assigned to this taxon.
 - `family`, `nfamily`, `genus`, `ngenus`, `species`, `nspecies`: IDs of family / genus / species with most reads assigned to, and numbers of reads assigned.
