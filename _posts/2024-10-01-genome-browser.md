---
layout: post
title: a post with formatting and links
date: 2024-10-01
description: march & april, looking forward to summer
tags: formatting links
categories: sample-posts
---

### Genome Browser Overview

A genome browser is a tool that anchors various types of data (such as variation, transcription, methylation, transcription factor binding, and disease associations) to specific genomic locations. Before the era of consortiums, researchers faced challenges due to the lack of a standardized reference genome representation. The establishment of consortiums allowed the accumulation of years of sequence data from diverse sources, creating a common numbering system for each genomic position across species. However, this numbering can vary with different genome versions due to updates and error corrections, making it crucial to know the specific version of the genome to which your data is aligned.

### Main Genome Browsers

Some of the primary genome browsers include:

- **[UCSC Genome Browser](https://genome.ucsc.edu/) (RRID:SCR_005780)**
- **[Ensembl Genome Browser](https://useast.ensembl.org/index.html) (RRID:SCR_013367)**
- **[Epigenome Browser at WashU](https://epigenomegateway.wustl.edu/browser/) (RRID:SCR_006208)**
- **[Integrative Genomics Viewer (IGV)](https://igv.org/doc/desktop/) (RRID:SCR_011793)**

(I really don't know their differences. Do you?)

Our lab uses the UCSC browser, which I find has the best website design. Until now, I have used it for in-silico PCR sequence retrieval and looking for the stop codon of a specific gene. If you also want a gene model like me, do this:

1. **Reset the Genome Browser**:  
   Genome Browser --> Reset all user settings

2. **Open a Gene**:  
   Browse/Select Species --> worms --> C. elegans Assembly (WBcel235/ce11) --> gene name (or genome coordinates, rsIDs, HGVS terms, DNA sequence) --> GO  
   Example: gene model **stau-1**

It contains:
- Genome species and version number
- Position box
- Navigation tool buttons (zoom in, zoom out; go before 5' or after 3')
- Chromosome ideogram (red column shows the gene locus)
- Genome view window: Click-drag the scale ruler at the top to zoom into the region; click-drag + Alt to highlight the region.
- Pre-loaded tracks & track titles: The grey bars on the left can be used for selecting and configuring tracks. Why are there so many tracks? I just choose the first dataset.

The squares and arrows shown can be confusing, but here you are: gene model representation (image from melbournebioinformatics.org).

  <div class="col-sm mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/gene_model_representation.png" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>

By default, the UCSC Genome Browser displays the forward strand (5' to 3'), but it can be configured to show the negative strand (3' to 5'). To reverse the genome orientation, click the reverse button, and the Genome Browser image will flip to show either strand.

*At the end... Leave your comments if you happen to walk by here (especially if something is conceptually wrong! No one wants to be silently watched by someone thinking, "this guy doesn't know what she's talking about...")*

#### Citation

The content is adapted from [melbournebioinformatics.org](https://www.melbournebioinformatics.org.au/tutorials/tutorials/Genome_browsers/GenomeBrowsers_Intro/).
