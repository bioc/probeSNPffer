# probeSNPffer
[@hennlab](https://github.com/hennlab)
R package to identify methylation microarray probes whose sequences contain a SNP, given a BED file of variants. The methylation signal reported at such probes may be unreliable.
Authors: Gillian Meeks and Shyamalika Gopalan
[![DOI](https://zenodo.org/badge/617581082.svg)](https://zenodo.org/doi/10.5281/zenodo.10067503)
![probeSNPffer2](https://github.com/user-attachments/assets/f029c86c-7057-4c99-90dc-f90fe601ff11)
Install package:
```
if (!require("BiocManager"))
    install.packages("BiocManager")
BiocManager::install("probeSNPffer")
```
View vignette html once in R:

```
library(probeSNPffer)
browseVignettes(package = "probeSNPffer")
```

Diagram of probe coordinate scheme (adapted from: Planterose Jiménez et al. Genome Biology (2021) 22:274)
![vignette_probe_diagram](https://user-images.githubusercontent.com/31638949/226993687-b58b05ef-52b6-4024-af89-2a9e5bff0992.png)
Blue bars represent the genomic DNA strands, both forward (+) and reverse (-) and red bars represent the type 1 and type 2 probes and where they hybridize to the genomic strands. The probe regions are marked with reference to the forward strand coordiante of the target Cytosine, i.e. the probe region for Type 1, minus strand targeted probes extends [p-48, p+2].


