# exercise-1-technology-statistics-10x-chromium

### Group 6


___
# Part a
## summary of "how it works"
The 10X Chromium platform is used for advanced single cell genomics, where the genetic information of single cells is analyzed instead of a pooled sample of DNA. The technology works by partitioning single cells using microfluidics approaches. Each cell is then contained within a droplet combined with a single gel bead and additional reagents. These beads carry one specific barcode by which the droplet can be identified. This will allow the sequencing reads of each droplet to be mapped back to their origin.

## several links with a more general descriptions of this technique

[Van Andel Institute](https://rtsf.natsci.msu.edu/sites/_rtsf/assets/File/10X%20Chromium%20-%20Single%20Cell%20and%20Long%20Read%20Sequencing%20Applications%20and%20Workflow-4.pdf)

[Harvard](https://bauercore.fas.harvard.edu/10x-chromium-system)

[UCDavis](https://dnatech.genomecenter.ucdavis.edu/linked-read-sequencing-10x-genomics-gemcode/)

[10XGenomics](https://community.10xgenomics.com/t5/10x-Blog/Single-Cell-RNA-Seq-An-Introductory-Overview-and-Tools-for/ba-p/547)
___

# Part b
## what the ChIP-Seq does

#### Combination of chromatin immunoprecipitation (ChIP) with ultra high-throughput massively parallel sequencing.

#### Allows mapping of protein-DNA interactions in vivo on a genome scale.

#### Enables mapping of transcription factor binding, DNA binding proteins, RNA PoI II occupancy or Histone modification marks at genome scale.

## make the link (technology -> application -> statistics)

#### Chromatin Immunoprecipitation (ChIP) -> ChIP-Seq -> Poisson distributions, a negative binomial,...（ Used in peak calling process） 
##### Another application of ChIP-Seq is differential peak calling: This aims to identify differences in two ChIP-seq signals. To identify the differential peaks Hidden Markov Models (HMM) are used. 
##### HMM: A statistical model which consists of a unobservable Markov chain emitting (observable) symbols at each state depending only on the current state (Markov Property). Due to the presence of hidden random variables the optimization is not straightforward. A popular technique to be used is the Expectation Maximization Algorithm.

___



