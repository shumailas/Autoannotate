# Autoannotate
Autoannotate is an automated pipeline for annotation of genomic variants(SNPs, INDELs)

First of all set your working directory by following command
setwd("path of your directory")

Place the raw1.vcf and Mycobacterium.gtf files in that directory. In order to run the test code gtf
file is provided otherwise it can be downloaded directly from web.

After placing the files in working directory run the test.R script by following command.

source("test.R")

The packages required will be installed as the script will run.


Wait untill the results are obtained. 

The speed of internet should be good as it extracts some information from the web.


The second script provean.R contains the example about how the provean tool will be accessed. It contains
example of a single protein and will work for the rest of protein in a similar way.
