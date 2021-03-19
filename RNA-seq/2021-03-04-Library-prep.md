# Library preparation


## SMART-seq technologies

Using Smart-seq, smart-seq2 or library preparation method Library preparation 


SMARTer® Ultra® Low RNA kit is known as Smart-Seq
SMART-Seq® v4 Ultra® Low Input RNA Kit improved Smart-seq2
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5449089/


## Fluidigm C1

## sci-RNA-seq3 (3 prime end method)
sci-RNA-seq [Cao et al., 2017](https://doi.org/10.1126/science.aam8940)


Library preparation

1) Annealing of oligo(dT) primer

Oligo(dT) primers may bind to internal and 3' end poly A sequences. This introduces bias to mRNAs that contain poly A sequences [Nam et al., 2002](https://doi.org/10.1073/pnas.092140899)
![[Pasted image 20210319131814.png]]

reverse transcription (RT) primer is added initially and can include distinct components:
- Either have the TSO (10x 3')

There are two main components, the gel bead and the RT primer.

In the 10x library preparation method, each gel bead oligo has a common sequence of:
- a partial Illumina read 1 sequence
- 10x barcode
- UMI


Main steps in library preparation
1) oligo(dT) priming
2) reverse transcription
3) cDNA amplification
4) Tagmentation and adapter ligation
5) Amplification of 3'end and sample barcoding
6) Pooling of libraries and sequencing



--- 
###### Oligo(dT) priming and reverse transcription
Use of template switching oligos (TSOs) to increase coverage of the 5'end of the transcripts[^1]
![](../TSO_1.png)
![](../TSO_2.png)


Depending on the assay (3' vs 5' end) the:
1) Oligo(dT) sequence in bound to the gel bead and the TSO is in the RT primer
2) TSO is bound in the gel bead and oligo(dT) sequence is in the RT primer


---
###### cDNA amplification



On step 4
the transposase Tn5 

Combinational indexing:
- RT barcode
- PCR barcodes (i5 + i7)
- Tn5 barcoders

indexed hairpin ligation

[^1]: https://eu.idtdna.com/pages/education/decoded/article/use-of-template-switching-oligos-(ts-oligos-tsos)-for-efficient-cdna-library-construction