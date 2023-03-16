---
layout: page
title: maize
description: maize aDNA research
img: assets/img/maize_logo.jpg
importance: 1
category: research
---


Master project to work with Shyam Gopalakrishnan and Jazmín Ramos Madrigal at <a href="https://globe.ku.dk/research/hologenomics/gopalakrishnan-group/">The Globe Institute</a>

Title: **Imputation of ancient maize genomes**

**Background**: Maize (*Zea mays*) started its domestication process around 9000 years ago, when people in Southwestern Mexico started cultivating a wild grass (*Zea mays* subsp. *parviglumis*). Domesticated maize is so morphologically different from its wild ancestor (see figure below), that it took more than a decade of research to find the maize wild ancestor. Even though today it is widely accepted that maize was domesticated from a wild maize subspecies (*Zea mays* subsp. *parviglumis*) growing in lowland Southwest Mexico, tracing the early steps into its domestication remains challenging.

<div  style="text-align:center" class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="center" src="{{ '/assets/img/F1_large.jpg' | relative_url }}" width="250" height="300" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
Maize morphological changes during domestication. Figure on the left show teosinte or wild maize (<i>Zea mays</i> subsp. <i>parviglumis</i>) and figure on the right shows domesticated maize.
Photo credit: <a href="https://doi.org/10.1073/pnas.0901122106">Tian F <i>et al.</i> PNAS 2009</a>.
</div>
One of the main challenges is that current genomes from ancient maize are low coverage and contain many missing genotypes. The aim of this project is to test imputation (*i.e.* the process of inferring missing genotypes) methods on ancient maize genomes which will allow us to trace changes in maize genetic diversity through time and space. In particular, we will test two methods (<a href="https://odelaneau.github.io/GLIMPSE/">GLIMPE</a> and <a href="http://mathgen.stats.ox.ac.uk/impute/impute_v2.html">Impute2</a>) to find the parameters that yield the most accurate results. The imputed data will be used to trace the genetic changes associated with the morphological changes during the early stages of maize domestication.

The project is envisioned as a five steps process:

-	Starting from already available data from ancient and modern maize, create a test dataset downsampling one high-coverage modern and one medium-coverage ancient sample at different coverages for one chromosome.
-	Design a strategy to test different parameters and the two methods (GLIMPE and Impute2) on the test dataset
-	Run the tests on each of the downsampled datasets.
-	Evaluate the results by comparing the imputed data with genotypes estimated for the high-coverage data.
- Apply the best performing method/parameters to a larger dataset of ancient maize genomes and use the data to look for changes in allele frequencies associated with domestication.

The project is designed to be a full year of work (30 ECTS).

Candidate profile:
We are looking for someone interested in learning how to analyse high-throughput sequencing data, genomics, domestication and ancient DNA, with a background in bioinformatics or with basic programming skills (*e.g.* bash, R and/or python).

Competences you will get from working on this project:
- How to work on a High-Performance Computer cluster
- How to work with high-throughput sequencing data
- How to work with ancient DNA sequencing data
- How to perform imputation

For more information contact Jazmín Ramos Madrigal [jazmin.madrigal at sund.ku.dk] or Shyam Gopalakrishnan [shyam.gopalakrishnan at sund.ku.dk].
