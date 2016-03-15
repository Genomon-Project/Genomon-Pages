---
layout: page
image:
  feature: genomon-8fps-1100px-once.gif
headline: Genomon 
subtitle: The Zen of Cancer Genome Sequence Analysis 
search_omit: true
---

Genomon is a suite of bioinformatics tools for analyzing cancer genome and RNA sequencing data.

<ul style="list-style-type: none;">

<li style="margin: 10px; padding: 10px; background-color: #EFEFEF;">
<center><h2>Easy to use!</h2></center>
<div align="center"><img src="../images/iconmonstr-laptop-4-96.png"></div>
<br>
Genomon is now easier than ever to use.<br>
You just need to prepare list of input sequence data paths and just type:
<pre style="margin: 15px; padding: 5px; background-color: #FFFFFF;">
genomon_pipeline dna input.csv output_dir
</pre>
</li>

<li style="margin: 10px; padding: 10px; background-color: #EFEFEF;">
<center><h2>Large scale analysis!</h2></center>
<div align="center"><img src="../images/iconmonstr-server-7-96.png"></div>
<br>
Genomon is now highly optimized and efficiently utilizes ruffus package for job scheduling. <br>
You can analyze several hundreds of genomic and transcriptome sequencing data simultaneously. 
</li>

<li style="margin: 10px; padding: 10px; background-color: #EFEFEF;">
<center><h2>Flexible!</h2></center>
<div align="center"><img src="../images/iconmonstr-control-panel-11-96.png"></div>
<br>
Genomon is extensible. So you can easily incorporate your favorite modules into Genomon. <br>
Also you can easily deploy Genomon to your own cluster other than HGC supercomputer. 
</li>
</ul>

# Overview

Genomon enables us to perform sensitive and accurate detection of most types of genomic variants
(single nucleotide variants, short indels, mid-size (20bp - 300bp) indels and large scale structural variations),
and transcriptomic changes (gene fusions, aberrant splicing patterns),
and fairly good performance is demonstrated 
through [a large number of important cancer genome projects](http://www.ncbi.nlm.nih.gov/pubmed?term=(Ogawa%2C%20Seishi%5BAuthor%5D)%20AND%20Miyano%2C%20Satoru%5BAuthor%5D).


Genomon adopts efficient job scheduling framework that enables us easily analyzing several hundreds of 
genome and transcriptome sequencing data simultaneously.
Genomon is easy to install and after installing, 
users can start analysis just preparing simple sample configuration files.

Also, Genomon can be easily extensible and developers can freely re-distribute throught GPLv3 license,

