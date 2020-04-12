---
title: "Quantifying the tradeoff between sequencing depth and cell number in single-cell RNA-seq"
date: 2019-01-01
publishDate: 2020-04-12T12:39:22.441861Z
authors: ["Valentine Svensson", "Eduardo da Veiga Beltrame", "Lior Pachter"]
publication_types: ["2"]
abstract: "The allocation of a sequencing budget when designing single cell RNA-seq experiments requires consideration of the tradeoff between number of cells sequenced and the read depth per cell. One approach to the problem is to perform a power analysis for a univariate objective such as differential expression. However, many of the goals of single-cell analysis requires consideration of the multivariate structure of gene expression, such as clustering. We introduce an approach to quantifying the impact of sequencing depth and cell number on the estimation of a multivariate generative model for gene expression that is based on error analysis in the framework of a variational autoencoder. We find that at shallow depths, the marginal benefit of deeper sequencing per cell significantly outweighs the benefit of increased cell numbers. Above about 15,000 reads per cell the benefit of increased sequencing depth is minor. Code for the workflow reproducing the results of the paper is available at https://github.com/pachterlab/SBP_2019/."
featured: false
publication: "*bioRxiv*"
url_pdf: "http://biorxiv.org/content/early/2019/09/09/762773.abstract"
doi: "10.1101/762773"
---

