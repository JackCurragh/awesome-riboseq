# Awesome Ribo-Seq
A list of bioinformatic tools for working with Ribo-Seq data. Please feel free to make updates 
(a work in progress)



## Data Resources and Visualisation Environments 
| Tool                  | Code                                                                      | Reference                                                 | Note(s)                                                                                                               |
| -------------         | -------------                                                             | -------------                                             | -------------                                                                                                         |
| Trips-Viz             |  [Code](https://github.com/riboseqorg/Trips-Viz)                          |   [Reference](https://doi.org/10.1093/nar/gkab323)        | Written in Python; Browser only; [Link](https://trips.ucc.ie); Transcriptome                                          |
| GWIPS-viz             |  [Code](https://github.com/riboseqorg/GWIPS-viz)                          |   [Reference](https://doi.org/10.1093/nar/gkt1035)        | Based on UCSC Genome Browser; Browser only; [Link](https://gwips.ucc.ie); Genome                                      |
| RiboCrypt             |  [Code](https://github.com/m-swirski/RiboCrypt)                           |   [Reference]()                                           | Written in R; Available in Bioc; Genome aligned; Visualisation in both                                                |
| RPFdb                 |  [Code]()                                                                 |   [Reference](https://doi.org/10.1093/nar/gky978)         | Browser only; Counts and Called ORFs (RibORF) available per study; Genome; [Link](http://sysbio.gzzoc.com/rpfdb/)     |
| HRPDviewer            |  [Code](http://cosbi4.ee.ncku.edu.tw/HRPDviewer/user/help_p1#collect2)    |   [Reference](https://doi.org/10.1093/database/bay074)    | Pipeline available in .zip only' Written in Python; Transcriptome                                                     |
| RiboSeqDB             |  [Code]()                                                                 |   [Reference](https://doi.org/10.12704/vb/e18)            | Appears to be defunct                                                                                                 |
| TranslatomeDB         |  [Code]()                                                                 |   [Reference](https://doi.org/10.1093/nar/gkx1034)        | Transcriptome aligned with FANSe3; [Link](http://translatomedb.net/)                                                  |
| svist4get             |  [Code](https://github.com/art-egorov/svist4get)                          |   [Reference](https://doi.org/10.1186/s12859-019-2706-8)  | Command line app; Genomic                                                                                             |       

## Data Processing and Analysis
| Tool                          | Code                                                                              | Reference                                                     | Note(s)                                                                                                   |
| -------------                 | -------------                                                                     | -------------                                                 | -------------                                                                                             |
| riboviz                       |  [Code](https://github.com/riboviz/RiboViz)                                       |   [Reference](https://doi.org/10.1093/bioinformatics/btac093) | Nextflow (DSL1); End-to-end processing and analysis                                                       |
| Shoelaces                     |  [Code](https://bitbucket.org/valenlab/shoelaces/src/master/)                     |   [Reference](https://doi.org/10.1186/s12864-018-4912-6)      | Written in python                                                                                         |
| ORFik                         |  [Code](https://github.com/Roleren/ORFik)                                         |   [Reference](https://doi.org/10.1186/s12859-021-04254-w )    | Written in R; Available on Bioc; End-to-end                                                               |
| RiboProfiling                 |  [Code](https://bioconductor.org/packages/release/bioc/html/RiboProfiling.html)   |   [Reference](https://doi.org/10.12688/f1000research.8964.1)  | Written in R; Available on Bioc; Analysis Package                                                         |
| SystemPipeR                   |  [Code](https://bioconductor.org/packages/release/bioc/html/systemPipeR.html)     |   [Reference](https://doi.org/10.1186/s12859-016-1241-0)      | Written in R; Available on Bioc; End-to-end                                                               |
| RiboStreamR                   |  [Code](https://github.com/pjperki2/riboStreamR)                                  |   [Reference](https://doi.org/10.1186/s12864-019-5700-7)      | Written in R; Available as web app                                                                        |
| RiboSeqR                      |  [Code](https://bioconductor.org/packages/release/bioc/html/riboSeqR.html)        |   [Reference]()                                               | Written in R; Available in Bioc; Analysis and visualisation                                               |
| RiboPip                       |  [Code](https://github.com/stepf/RiboPip)                                         |   [Reference]()                                               | Written in Ruby; Comes with Dockfile; End-to-end                                                          |
| RiboGalaxy                    |  [Code](https://github.com/riboseqorg/RiboGalaxy)                                 |   [Reference](https://doi.org/10.1080/15476286.2016.1141862)  | Galaxy Platform; Tools in toolshed; Data Processing; [Link](https://ribogalaxy.genomicsdatascience.ie/)   |
| Plastid                       |  [Code](https://github.com/joshuagryphon/plastid)                                 |   [Reference](https://doi.org/10.1186/s12864-016-3278-x)      | Written in Python; Packaged on PyPi; Analysis                                                             |
| RiboTools                     |  [Code]()                                                                         |   [Reference](https://doi.org/10.1093/bioinformatics/btv174)  | Galaxy Platform; Tools in toolshed; Analysis                                                              |
| RiboFlow, RiboR and RiboPy    |  [Code](https://github.com/ribosomeprofiling)                                     |   [Reference](https://doi.org/10.1093/bioinformatics/btaa028) | Ecosystem of tools; Nextflow (DSL1), R and Python; End-to-end                                             |
| RiboToolKit                   |  [Code]()                                                                         |   [Reference](https://doi.org/10.1093/nar/gkaa395)            | Browser only; End-to-end; [Link](http://rnainformatics.org.cn/RiboToolkit/)                               |
| XPRESSpipe                    |  [Code](https://github.com/XPRESSyourself/XPRESSpipe/tree/main/xpresspipe)        |   [Reference](https://doi.org/10.1371/journal.pcbi.1007625)   | Written in Python, R & C++; End-to-end                                                                    |


## Differential Translation
| Tool                           | Code                                                                         | Reference                                                     | Note(s)                                                                           |
| -------------                  | -------------                                                                | -------------                                                 | -------------                                                                     |
| Anota2Seq                      |  [Code](https://bioconductor.org/packages/release/bioc/html/anota2seq.html)  |   [Reference](https://doi.org/10.1093/nar/gkz223)             | Written in R; Avaialble in Bioc                                                   |
| Babel                          |  [Code](https://cran.r-project.org/web/packages/babel/index.html)            |   [Reference](https://doi.org/10.1093/bioinformatics/btt533)  | Written in R; Available in CRAN; EdgeR                                            |
| RiboDiff                       |  [Code](https://github.com/ratschlab/RiboDiff)                               |   [Reference](https://doi.org/10.1093/bioinformatics/btw585)  | Python2, Galaxy, [Link](https://galaxy.inf.ethz.ch/?tool_id=ribodiff), GLM        |
| Riborex                        |  [Code](https://github.com/smithlabcode/riborex)                             |   [Reference](https://doi.org/10.1093/bioinformatics/btx047)  | Written in R; Conda installation; DEseq2, EdgeR, Voom;                            |
| RIVET                          |  [Code](https://github.com/ruggleslab/rivet)                                 |   [Reference](https://doi.org/10.1186/s12864-018-5166-z)      | Written in R; R Shiny app; Link defunct; EdgeR/Limma                              |
| Xtail                          |  [Code](https://github.com/xryanglab/xtail)                                 |   [Reference](https://doi.org/10.1038/ncomms11194)            | Written in R; Available in DockerHub; Probability Distribution based              |



## Quality Control

| Tool                  | Code                                                  | Reference                                                 | Note(s)                                                       |
| -------------         | -------------                                         | -------------                                             | -------------                                                 |
| MQc                   |  [Code](https://github.com/Biobix/mQC)                |  [Reference](https://doi.org/10.1016/j.cmpb.2018.10.018)  | Written in Perl, Python 2, R; Available on Galaxy and Conda   |
| Ribo-seQC             |  [Code](https://github.com/ohlerlab/RiboseQC)         |  [Reference](https://doi.org/10.1101/601468)              | Written in R                                                  |
| RiboQC                |  [Code](https://github.com/carinelegrand/RiboVIEW)    |  [Reference](https://doi.org/10.1093/nar/gkz1074)                         | Written in R; Part of RiboVIEW                                |
| ribosomeProfilingQC   |  [Code](https://rdrr.io/bioc/ribosomeProfilingQC/)    |  [Reference](https://doi.org/10.18129/B9.bioc.ribosomeProfilingQC)        | Written in R; Available on Bioc; Reference in Bioc link       |
| ORFikQC               |  [Code](https://github.com/Roleren/ORFik)             |  [Reference](https://doi.org/10.1186/s12859-021-04254-w)                  | Written in R; Available on Bioc; Part of ORFik                |

Note: Many more tools carry out QC as part of their functionality. Above are those that QC specific modules (that I have seen so far). 

## Offset Determination
| Tool                  | Code                                                  | Reference                                                 | Note(s)                                                       |
| -------------         | -------------                                         | -------------                                             | -------------                                                 |
|                       |  [Code]()                                             |   [Reference]()                                             |                                                             |


## ORF Calling
| Tool                  | Code                                                  | Reference                                                 | Note(s)                                                       |
| -------------         | -------------                                         | -------------                                             | -------------                                                 |
|                       |  [Code]()                                             |   [Reference]()                                             |                                                             |

## ORF Databases
| Tool                  | Code                                                  | Reference                                                 | Note(s)                                                       |
| -------------         | -------------                                         | -------------                                             | -------------                                                 |
| sORFs.org             |  [Code]()                                             |   [Reference]()                                             |                                                             |
| OpenProt              |  [Code]()                                             |   [Reference]()                                             |                                                             |
|                       |  [Code]()                                             |   [Reference]()                                             |                                                             |


## Rough 

**Row template:**
|                       |  [Code]()                                             |   [Reference]()                                             |                                                             |


#### Unsorted list:
- Ribo-TISH (annotation)
- Rfoot
- Ribodeblur (offset)
- Proteoformer (annotation)
- DeepRibo (annotation)
- RiboZINB (translated isoform)
- Ribofy (https://github.com/ncrnalab/ribofy)
- orfRater
- RiboDiPa

[L](http://rnainformatics.org.cn/RiboToolkit/links.php)


DeepRibo	Detection of translated ORFs in bacterial genomes	https://github.com/Biobix/DeepRibo	Clauwaert et al. (2019)
orfRater	Detection of translated ORFs based on linear regression	https://github.com/alexfields/ORF-RATER	Fields et al. (2015)
ORFScore	Scoring translated ORFs based on triplet periodicity	https://rdrr.io/bioc/ORFik/man/orfScore.html	Bazzini et al. (2014)
PreTis	Detection of translation initiation starts based on linear regression	http://service.bioinformatik.uni-saarland.de/pretis/	Reuter, Biehl, Koch, and Helms (2016)
PRICE	Detection of translated ORFs using EM algorithm	https://github.com/erhard-lab/price	Erhard et al. (2018)
Proteoformer	Detection of translated ORFs with support from mass-spec data	https://github.com/Biobix/proteoformer	Crappe et al. (2015); Verbruggen et al. (2019)
REPARATION	Detection of translated ORFs in bacterial genomes	https://github.com/Biobix/REPARATION	Ndah et al. (2017)
RiboCode	Detection of translated ORFs based on triplet periodicity	https://github.com/xryanglab/RiboCode	Xiao et al. (2018)
riboHMM	HMM-based detection of translated ORFs	https://github.com/rajanil/riboHMM	Raj et al. (2016)
RibORF	SVM-based identification of translated ORFs	https://github.com/zhejilab/RibORF	Ji, Song, Regev, and Struhl (2015)
Ribosome profiling analysis framework	Detection of translated ORFs based on triplet periodicity	https://github.com/LUMC/ribosome-profiling-analysis-framework	de Klerk et al. (2015)
RiboTaper	Detection of translated ORFs based on spectral analysis of Ribo-Seq signal using multitaper	https://ohlerlab.mdc-berlin.de/software/RiboTaper_126/	Calviello et al. (2016)
Ribo-TISH	Is able to use Ribo-Seq data enriched at starts of initiation in addition to regular Ribo-Seq	https://github.com/zhpn1024/ribotish	P. Zhang et al. (2017)
RiboWave	Detection of translated ORFs based on spectral analysis of Ribo-Seq signal with wavelet transformation	https://github.com/lulab/Ribowave	Xu et al. (2018)
Rp-Bp	Bayesian approach for detecting translated ORFs.	https://github.com/dieterich-lab/rp-bp	Malone et al. (2017)
SPECtre	Detection of translated ORFs based on spectral analysis of Ribo-Seq signal	https://github.com/mills-lab/spectre	Chun et al. (2016)
uORF-seqr	Regression-based detection of translated ORFs	https://github.com/pspealman/uorfseqr	Spealman et al. (2018)