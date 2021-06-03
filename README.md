## Single-nucleotide conservation state annotation of the SARS-CoV-2 genome

We applied [ConsHMM](https://github.com/ernstlab/ConsHMM) to sequence alignments of coronaviruses (CoV) and learned annotations for the SARS-CoV-2 genome that capture underlying alignment patterns among CoV and their relationship to observed SARS-CoV-2 mutations.

Files in this repository or the following public URL can be used to view the annotations on [UCSC SARS-CoV-2 Genome Browser](https://genome.ucsc.edu/cgi-bin/hgGateway?db=wuhCor1). 
- [30 ConsHMM conservation states learned from the Sarbecovirus sequence alignment](https://public.hoffman2.idre.ucla.edu/ernst/R0RG6/wuhCor1.sarbecovirusConsHMM.bed)
- [30 ConsHMM conservation states learned from the vertebrate CoV sequence alignment](https://public.hoffman2.idre.ucla.edu/ernst/R0RG6/wuhCor1.vertebrateCoVConsHMM.bed)
- Mutation depletion score track based on significant enrichment/depletion of nonsingleton SARS-CoV-2 mutations
  - [Based on all conservation states](https://public.hoffman2.idre.ucla.edu/ernst/R0RG6/wuhCor1.mutDepletionConsHMM.bed)
  - [Based on states learned from Sarbecovirus alignment](https://public.hoffman2.idre.ucla.edu/ernst/R0RG6/wuhCor1.mutDepletionSarbecovirusConsHMM.bed)
  - [Based on states learend from vertebrate CoV alignment](https://public.hoffman2.idre.ucla.edu/ernst/R0RG6/wuhCor1.mutDepletionVertebrateCoVConsHMM.bed)

## Reference
Kwon S.B., Ernst J. Single-nucleotide conservation state annotation of the SARS-CoV-2 genome. *Communications Biology*, 4:698, 2021. ([link](https://www.nature.com/articles/s42003-021-02231-w))
