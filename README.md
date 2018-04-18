# dahak-eel-pond
working dir for project to turn eel pond protocols (nonmodel RNAseq differential expression analysis) into a dahak-style containerized workflow

[eel-pond protocols](http://eel-pond.readthedocs.io/en/latest/)
* [DIBSI, nonmodel RNAseq workshop, July 2017](http://dibsi-rnaseq.readthedocs.io/en/latest/)
* [SIO-BUG, nonmodel RNAseq workshop, October 2017](http://rnaseq-workshop-2017.readthedocs.io/en/latest/index.html)

**Workflows:**
  - Read Quality Trimming and Filtering
  - Digital Normalization
  - Assembly
  - Quality Assessment
  - Annotation
  - Transcript Quantification 
  - Differential Expression



Current Status: 

Imported workflow style and scripts from dahak-taco (4-18-18). These are still under development for dahak & subject to change.

**To Do:**

Get dahak portion working:  

  - test read-filtering workflow (directly from dahak-taco)
  - write installation / requirements files

Build RNAseq workflows:  
  
  - locate or write singularity recipes for all required RNA programs (e.g. Trinity, Salmon, etc)
  - write snake rules for each individual program
  - write Snakefile for each workflow




