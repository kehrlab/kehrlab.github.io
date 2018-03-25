---
layout: page
title: Research
long-title: Research Focus
---

The genomes of any two humans differ by thousands of structural variants (SVs) including deletions, duplications, insertions, inversions, translocations and more complex rearrangements that may have phenotypic consequences. However, with the current technologies and algorithms we are only beginning to understand the extent and evolution of SVs and their impact on phenotypes. Our abilities to identify SVs are limited due to the high repeat content in the (human) genome, due to noise in the data that leads to a high rate of false predictions as well as to inaccurate genotyping, and due to the fast-growing amount of newly generated data. Our lab addresses these challenges by developing new algorithms for the analysis of modern sequence data. We implement, test and make our methods available so that we and others can apply them to data sets in collaborative biomedical research projects. 

{% include research_figure.html image="NRNRs.png" caption="Examples of structural variants called with PopIns in WGS data of 15,219 Icelanders" source="Kehr et al., Nature Genetics (2017)" source-link="https://www.nature.com/articles/ng.3801" %}

### Joint calling approaches

We take advantage of the magnitude of data that is generated, and develop SV identification and genotyping approaches that analyze data from many samples jointly. The idea behind these approaches is that one can better differentiate between signal and noise when looking at data sets of several samples together. Joint approaches are already well-established for SNV and indel calling, but much less for SVs. We are extending and improving the series of SV identification and genotyping programs that includes [PopIns](https://github.com/bkehr/PopIns), [PopAlu](https://github.com/aimeida/PopAlu), and [PopSTR](https://github.com/DecodeGenetics/popSTR). 

### Exploration of new data types

Identification of complex SVs and SVs in repetitive regions requires long-range sequence information. Several data types from new technologies now offer long-range information (e.g. long reads, linked short reads, or optical genome maps). We explore such data types and develop algorithms for identifying those SVs that are invisible or ambiguous in standard short read data.

### Collaboration in disease projects

In addition to algorithm development, we apply our methods to data sets generated in various disease projects of our collaborators.

{% include research_figure.html image="CASP8.png" caption="A mobile element insertion in the CASP8 gene that is associated with protection against prostate cancer" source="Stacey et al., Human Molecular Genetics (2016)" source-link="https://academic.oup.com/hmg/article/25/5/1008/2384615" %}
