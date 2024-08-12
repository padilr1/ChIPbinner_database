# ChIPbinner_database

Copyright (C) 2024 Reinnier Padilla

Database for ChIPbinner. Contains example data as well as curated databases from Ensembl, Encode and RepeatMasker for use with ChIPbinner.

* 'reference_windows' contains reference windows that can be used to transform aligned BAM files into binned BED files.

* 'example_data' contains complete datasets from Farhangdoost et al. (https://doi.org/10.1016/j.celrep.2021.108769):
  * HNSCC H3K36me2 ChIP-seq samples binned into 10kb windows
  * normalized bigWig files
  * complete pooled BED file of genomic coordinates
  * complete matrix file of binned scores
  * complete clustering results from running HDBSCAN on the whole dataset
  
* 'functional_db' contains curated databases (as R objects) for input into the 'enrich_clust()' function of ChIPbinner.
  * ensemblDB from https://useast.ensembl.org/info/genome/index.html"
  * ccreDB (candidate cis-regulatory elements) from "https://useast.ensembl.org/info/genome/index.html"
  * repeatsDB (repeatMasker) from https://www.repeatmasker.org/
