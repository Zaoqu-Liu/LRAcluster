### Provenance

This repository is a copy of **LRAcluster 1.0** (DESCRIPTION dated 2015-01-06; authors Dingming Wu and Dongfang Wang; license GPL (>= 2)), the R package accompanying Wu et al., *BMC Genomics* 2015 (see Citation below), kept here so that [MOFS](https://github.com/Zaoqu-Liu/MOFS) can install it with `devtools::install_github()`. The authors' distribution page (<http://bioinfo.au.tsinghua.edu.cn/software/lracluster/>) could not be reached when this note was written, and the package is not on CRAN or Bioconductor, so a byte-level comparison with the original download was not possible. What is verifiable: the package files (`DESCRIPTION`, `NAMESPACE`, `R/`, `man/`, `data/`) were uploaded in a single commit and have not been edited since; only this README changed afterwards.

### Installation
```r
devtools::install_github("Zaoqu-Liu/LRAcluster")
```

### Citation
Wu D, Wang D, Zhang MQ, Gu J. Fast dimension reduction and integrative clustering of multi-omics data using low-rank approximation: application to cancer molecular classification. BMC Genomics. 2015;16:1022. Published 2015 Dec 1. doi:10.1186/s12864-015-2223-8
