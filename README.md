[//]: # (TODO: Bioconductor support?)
[//]: # (TODO: Some examples)

<p align="center">
  <a href="https://github.com/broadinstitute/CommunityAMARETTO/">
    <img height="150" src="https://github.com/broadinstitute/CommunityAMARETTO/blob/develop/inst/extdata/CommunityAMARETTO_logo.png">
  </a>
  <h1 align="center"></h1>
</p>




# Community-AMARETTO

The goal of the Community-AMARETTO algorithm (Champion et al., EBioMedicine 2018) is to identify cell circuits and their drivers that are shared and distinct across biological systems. Specifically, Community-AMARETTO takes as input multiple regulatory networks inferred using the AMARETTO algorithm that are based on multi-omics and imaging data fusion. Next, Community-AMARETTO learns communities or subnetworks, in particular, regulatory modules comprising of cell circuits and their drivers, that are shared and distinct across multiple regulatory networks derived from multiple cohorts, diseases, or biological systems more generally, using the Girvan-Newman "edge betweenness community detection" algorithm (Girvan and Newman, Physical Review E. 2004).

REFERENCES

GitHub:<br/>
AMARETTO: https://github.com/gevaertlab/AMARETTO<br/>
Community-AMARETTO: https://github.com/broadinstitute/CommunityAMARETTO

GenePattern: <under development><br/>
AMARETTO: https://beta.genepattern.org/gp/pages/index.jsf?lsid=urn:lsid:broad.mit.edu:cancer.software.genepattern.module.analysis:00378:0.52<br/>
Community-AMARETTO: https://beta.genepattern.org/gp/pages/index.jsf?lsid=urn:lsid:broad.mit.edu:cancer.software.genepattern.module.analysis:00380:999999999
  
Docker: <under development><br/>
AMARETTO: https://hub.docker.com/r/genepattern/docker-amaretto<br/>
Community-AMARETTO: https://hub.docker.com/r/genepattern/community-amaretto

## Installation

You can install the released version of CommunityAMARETTO from github:

``` r
library(devtools)
install_github("CommunityAMARETTO")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
## basic example code
```

