# RNA-seq methods
QUESTIONS:
- Why does SMARTer gives a bit of bias?

The different platforms can be classified according to the type of platform used from microwell plates, microfluidics chop or nanoliter droplets.



There are two types[^1][^2][^3]:
- Full-length: even coverage of the transcripts
- Tag-based (3' or 5' -end): biases coverage to the 3 or 5 prime end region of the transcripts.

Depending on the biological question of interest and depending on how the transcripts of interest are transcribed, the choice of protocol should be further based on the read coverage achieved by each protocol.
#### Reverse transcription (RT) and cDNA amplification
SMART-Seq v4 Ultra low Input RNA kit can be used here

#### Sequencing library preparation
Nextera XT DNA Library Preparation kit

#### Coverage bias
On the tag-based protocols, oligo-dT beads are used to bind polyA+ mRNAs. Oligo-dTs can also bind to internal poly-A sites, in which case cDNA synthesis starts from the intermediate region of the mRNA and ends at the 5' end or before reaching the 5' end region, due to **RT enzyme stalling**. (Insert here a scheme?)

There mRNAs are then fragmented and cDNA synthesis is then done (verify)


QUESTIONS: 
- besides oligo-dt, are there other caused for introducing bias? RHex are random hexamers
- WHat is exactly stalling of the RT enzyme?

The following are full length.
- [[2021-03-04-SMART-seq technology]]
- [[SUPeR-seq]]
- [[MATQ-seq]]

The following are full length with some bias
- [[Quartz-seq]]
- [[Quartz-seq2]]
- [[STRT-seq]] a bit less coverage of the 5 prime end

The following are 5' prime end tag
- [[Fluidigm-C1]]

The following are 3' prime end tag
- [[10x genomics]]
- [[Drop-seq]]
- [[CEL-seq]]
- [[CEL-seq2]]
- [[inDrops]]
- [[SCRB-seq]]
- [[MARS-seq]]
- [[MARS-seq2]]
- [[Microwell-seq]]
- [[sci-RNA-seq3]]

Multimodal techniques
- [[SNARE-seq]][^4]
- Patch-seq

- 






Several papers compare the different protocols/methods
[^1]: https://www.nature.com/articles/nmeth.4220
[^2]: https://pubmed.ncbi.nlm.nih.gov/32375335/
[^3]: https://physiology.med.cornell.edu/faculty/skrabanek/lab/angsd/resources_2019/Lafzi2018_scRNAseqDesign.pdf
[^4]: https://www.nature.com/articles/s41587-019-0290-0#Sec2

