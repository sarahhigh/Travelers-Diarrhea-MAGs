Interactive annotation tables of individual bins. Columns:
 - `Ctg`, `ID`: IDs of current contig and ORF.
 - `Location`: Start, end and strand of the ORF predicted using [Prodigal](https://github.com/hyattpd/Prodigal).
 - `Gene`, `Product`: Annotated using [Prokka](https://github.com/tseemann/prokka).
 - `Taxonomy`: Lowest-rank taxonomic group with at least 75% reads assigned to.
 - `KO`, `Module`, `Pathway`: [KEGG](https://www.genome.jp/kegg/) orthology, module and pathway.
 - `Virulence`: Virulence factor genes detected using [VFDB](http://www.mgc.ac.cn/VFs/main.htm).
 - `Resistance`: Antibiotic resistance genes detected using [Resfams](http://www.dantaslab.org/resfams/).
 - `Plasmid`: Plasmid genes detected using [ACLAME](http://aclame.ulb.ac.be/).
 - `Virus`: Virus genes detected using [PHAST](http://phast.wishartlab.com/).