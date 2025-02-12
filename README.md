# ChAMP Package for DNA methylation analysis

ChAMP package is designed for conduct DNA methylation array analysis, providing service from data loading, to final gene set enrichment analysis .e.g.

More information could be find in [Bioconductor page](https://bioconductor.org/packages/release/bioc/html/ChAMP.html). Also we provided a more detailed guide in the [HTML vignette](https://bioconductor.org/packages/release/bioc/vignettes/ChAMP/inst/doc/ChAMP.html).

This fork is based on ChAMP version 2.36 and includes the fix for the SVD to work with R version ≥ 4.0

## Installation

Download the source code with this command line or through the github interface :

```
git clone https://github.com/eliopato/ChAMP.git
```

And install it with 
```
R CMD INSTALL ChAMP
```

or from R Studio directly:
```
install.packages('/path/to/ChAMP', repos=NULL, type='source')
```

Current latest version: `2.36`
