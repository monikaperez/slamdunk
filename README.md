## jkobject/slamdunk

A spike-in enabled and paired-end sequencing compliant version of slamdunk.

## Installation

`pip install git+https://github.com/jkobject/slamdunk`

! Make sure that you have installed [ngm](https://github.com/Cibiv/NextGenMap/wiki) too.

! if you have paired end reads or use hg38, please read the remarks bellow.

## Remark

You should think about trimming ends from your reads before running slamdunk.

See some additional tips and advices about running slamdunk in our issue report here:

- [Signal at alternate contigs lost #107](https://github.com/t-neumann/slamdunk/issues/107)
- [Multimapping influences output at read length of 152bp #106](https://github.com/t-neumann/slamdunk/issues/106)
- [Multimapping is not default and bed file isn't used #105](https://github.com/t-neumann/slamdunk/issues/105)


### t-neuman Slamdunk documentation

http://t-neumann.github.io/slamdunk

### citation:

please cite the initial paper from t-neuman: [Quantification of experimentally induced nucleotide conversions in high-throughput sequencing datasets](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2849-7) and our own paper on the topic [A distinct core regulatory module enforces oncogene expression in KMT2A-rearranged leukemia](https://www.biorxiv.org/content/10.1101/2021.08.03.454902v1.abstract)

Updated by:
- Jeremie Kalfon @jkobject
- Monika Perez
