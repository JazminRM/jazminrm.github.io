---
layout: page
title: grapevine
description: grapes aDNA research
img: assets/img/grapes_logo.jpg
importance: 2
category: research
---


Master project to work with Shyam Gopalakrishnan and Jazmín Ramos Madrigal at <a href="https://globe.ku.dk/research/hologenomics/gopalakrishnan-group/">The Globe Institute</a>

Title: **Developing a method to estimate the colour of ancient grape berries from genotype data using a support vector machine.**

**Background**: Wild grapes have dark red berries, while domesticated grapes can range from dark red to white. Dark red berries result from the accumulation of anthocyanin, regulated by the *MybA* genes, a cluster of transcription factors on chromosome X. Genetic variation on the *MybA* genes has been shown to lead to berries of different shades of red going from almost black to pink. Additionally, white berries are the result of the insertion of the *Gret1* retrotransposon in the upstream region of the *vvMybA1* gene, which inactivates the gene, thus leading to the lack of anthocyanins.


<div style="text-align:center" class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="center" src="{{ '/assets/img/BerryColor.jpg' | relative_url }}" width="561.275" height="314.6" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
Wild grapes have a functioning <i>MybA</i> genes and are dark red colour. Genetic variation on <i>MybA</i> genes in domesticated grapes lead to colours going from dark red to pink, and an insertion of <i>Gret1</i> element leads to white berries.
</div>


The goal of this project is to develop a method based on a support vector machine (SVM) that takes in genotype data from modern grapes and generates a model to predict the colour of the berries in ancient grapes.

The project is envisioned as a three steps process:

-	Write a script (on your preferred coding language) that takes genotype data from the *MybA* genes of modern grapes as well as information about their colour and utilises a SVM to generate a model to predict the colour based on the genotype data.
-	Test the model by applying it to a subset of the data for which the colour is known. In particular, test its robustness to missing data and potential sequencing error.
-	Test the method on a dataset of ancient grape samples.
-	(Optional) Depending on the results from step 2, consider creating an implementation that takes as input genotype-likelihoods instead of called genotypes.

The project is designed to be a full year of work (30 ECTS), however it can be adjusted to a smaller project (15 ECTS).

Candidate profile:
- Programming on bash and R, python, or similar is required
- Reading scientific literature

Competences you will get from working on this project:
- Learn how to work on a High-Performance Computer cluster
- Learn how to implement a support vector machine
- Learn how to work with high-throughput sequencing data
- Learn how to work with ancient DNA sequencing data

For more information contact Jazmín Ramos Madrigal [jazmin.madrigal at sund.ku.dk] or Shyam Gopalakrishnan [shyam.gopalakrishnan at sund.ku.dk].
