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
| Xtail                          |  [Code](https://github.com/xryanglab/xtail)                                  |   [Reference](https://doi.org/10.1038/ncomms11194)            | Written in R; Available in DockerHub; Probability Distribution based              |



## Quality Control

| Tool                  | Code                                                  | Reference                                                 | Note(s)                                                       |
| -------------         | -------------                                         | -------------                                             | -------------                                                 |
| MQc                   |  [Code](https://github.com/Biobix/mQC)                |  [Reference](https://doi.org/10.1016/j.cmpb.2018.10.018)  | Written in Perl, Python 2, R; Available on Galaxy and Conda   |
| Ribo-seQC             |  [Code](https://github.com/ohlerlab/RiboseQC)         |  [Reference](https://doi.org/10.1101/601468)              | Written in R                                                  |
| RiboQC                |  [Code](https://github.com/carinelegrand/RiboVIEW)    |  [Reference](https://doi.org/10.1093/nar/gkz1074)                         | Written in R; Part of RiboVIEW                                |
| ribosomeProfilingQC   |  [Code](https://rdrr.io/bioc/ribosomeProfilingQC/)    |  [Reference](https://doi.org/10.18129/B9.bioc.ribosomeProfilingQC)        | Written in R; Available on Bioc; Reference in Bioc link       |
| ORFikQC               |  [Code](https://github.com/Roleren/ORFik)             |  [Reference](https://doi.org/10.1186/s12859-021-04254-w)                  | Written in R; Available on Bioc; Part of ORFik                |

Note: Many more tools carry out QC as part of their functionality. Above are those that have individual QC specific modules (that I have seen so far). 

## Offset Determination
| Tool                  | Code                                                                  | Reference                                                                     | Note(s)                                                       |
| -------------         | -------------                                                         | -------------                                                                 | -------------                                                 |
| Ribodeblur            |  [Code](https://github.com/Kingsford-Group/ribodeblur)                |   [Reference](https://doi.org/10.1089/cmb.2016.0147)                          | Written in Python                                             |
| RiboProP              |  [Code](http://bioserv.mps.ohio-state.edu/RiboProP/)                  |   [Reference](https://doi.org/10.1093/bioinformatics/bty854)                  | Written in Julia; MNase Offset detection                      |
| RiboWaltz             |  [Code](https://github.com/LabTranslationalArchitectomics/riboWaltz)  |   [Reference](https://doi.org/10.1371/journal.pcbi.1006169)                   | Written in R; Available in Bioconda                           |
| Integer Programming   |  [Code](https://github.com/nabeel-bioinfo/Asite_IP_method)            |   [Reference](https://doi.org/10.1038/s41598-019-42348-x)                     | Written in Python; Paper contains comparison of methods       |
| Scikit-ribo           |  [Code](https://github.com/hanfang/scikit-ribo)                       |   [Reference](https://doi.org/10.1016/j.cels.2017.12.007)                     | Written in Python; Also estiamtes translation efficiency      |

Note: Many many tools carry out offset determinations. These ones advertise it as a main feature.

## ORF Calling
| Tool                                      | Code                                                                      | Reference                                                         | Note(s)                                                                                               |
| -------------                             | -------------                                                             | -------------                                                     | -------------                                                                                         |
| DeepRibo                                  |  [Code](https://github.com/Biobix/DeepRibo)                               |   [Reference](https://doi.org/10.1093/nar/gkz061)                 | Python3/PyTorch; Prokaryotes; Ribo-Seq + SD sequence                                                  |
| RiboTricer                                |  [Code](https://github.com/smithlabcode/ribotricer)                       |   [Reference](https://doi.org/10.1093/bioinformatics/btz878)      | Python; 3' periodicity based                                                                          |
| orfRater                                  |  [Code](https://github.com/alexfields/ORF-RATER)                          |   [Reference](https://doi.org/10.1016/j.molcel.2015.11.013)       | Python, Regression based                                                                              |
| PreTis                                    |  None Found                                                               |   [Reference](https://doi.org/10.1371/journal.pcbi.1005170)       | No code available; Webservice; Regression based TIS                                                   |
| PRICE                                     |  [Code](https://github.com/erhard-lab/price)                              |   [Reference](https://doi.org/10.1038%2Fnmeth.4631)               | Available as part of Gedi; Probablistic inference by EM                                               |
| Proteoformer                              |  [Code](https://github.com/Biobix/proteoformer)                           |   [Reference](https://doi.org/10.1074/mcp.RA118.001218)           | ORF calling for MS validation; Python, Perl                                                           |
| REPARATION                                |  [Code](https://github.com/Biobix/REPARATION)                             |   [Reference](https://doi.org/10.1093/nar/gkx758)                 | Reannoation of Bacterial Genomes; Perl                                                                |
| RiboCode                                  |  [Code](https://github.com/xryanglab/RiboCode)                            |   [Reference](https://doi.org/10.1093/nar/gky179)                 | Wilcoxon Signed rank test of 3 frames; Python; On Bioconda                                            |
| riboHMM                                   |  [Code](https://github.com/rajanil/riboHMM)                               |   [Reference](https://doi.org/10.7554/eLife.13328)                | Python2; Limits to 1 coding sequence per transcript                                                   |
| RibORF                                    |  [Code](https://github.com/zhejilab/RibORF)                               |   [Reference](https://doi.org/10.1002/cpmb.67)                    | Perl; 3' periodicity, uniformness;                                                                    |
| Ribosome profiling analysis framework     |  [Code](https://github.com/LUMC/ribosome-profiling-analysis-framework)    |   [Reference](http://dx.doi.org/10.1093/nar/gkv281)               | PHP, Organism must be on [Mutalyzer](https://mutalyzer.nl/)                                           |
| RiboTaper                                 |  [Code](https://ohlerlab.mdc-berlin.de/software/RiboTaper_126/)           |   [Reference](https://doi.org/10.1038/nmeth.3688)                 | R; Multitaper analysis of triplet; Bioconda, Galaxy;                                                  |
| Ribo-TISH                                 |  [Code](https://github.com/zhpn1024/ribotish)                             |   [Reference](https://doi.org/10.1038/s41467-017-01981-8)         | Python; TI-seq (TIS Hunter); Supports differential initiation analysis                                |
| RiboWave                                  |  [Code](https://github.com/lulab/Ribowave)                                |   [Reference](https://doi.org/10.1093/nar/gky533)                 | R, Perl, Shell; Wavelet Transform;                                                                    |
| Rp-Bp                                     |  [Code](https://github.com/dieterich-lab/rp-bp)                           |   [Reference](https://doi.org/10.1093/nar/gkw1350)                | Python; End-to-end pipeline; Bayesian Periodic fragment length and ribosome P-site offset Selection   |
| SPECtre                                   |  [Code](https://github.com/mills-lab/spectre)                             |   [Reference](https://doi.org/10.1186%2Fs12859-016-1355-4)        | Python; Spectral analysis of sliding windows                                                          |
| uORF-seqr                                 |  [Code](https://github.com/pspealman/uorfseqr)                            |   [Reference](https://doi.org/10.1101/gr.221507.117)              | R; ML-approach; Methods unclear as paper describes regression                                         |
| uORF4u                                    |  [Code](https://github.com/GCA-VH-lab/uorf4u)                             |   [Reference](https://doi.org/10.1101/2022.10.27.514069)          | Python; Not Ribo-Seq; Conservation based; One 5' UTR at a time                                        |
| ORFLine                                   |  [Code](https://github.com/boboppie/ORFLine)                              |   [Reference](https://doi.org/10.1093/bioinformatics/btab339)     | Shell, R, Perl, Python; End-to-end; Plastid + ORFscore                                                |
| RiboNT                                    |  [Code](https://github.com/songbo446/RiboNT/)                             |   [Reference](https://doi.org/10.3390/life11070701)               | Python; Noise tolerence                                                                               |

|                                           |  [Code]()                                                                 |   [Reference]()                                                   |                                                                                                       |


## ORF Databases
| Tool                  | Link                                                                  | Reference                                                 | Note(s)                                                       |
| -------------         | -------------                                                         | -------------                                             | -------------                                                 |
| sORFs.org             |  [Link](http://www.sorfs.org/#)                                       |   [Reference](https://doi.org/10.1093/nar/gkx1130)        | ORFs Detected with Proteoformer; Pride reprocessing           |
| OpenProt              |  [Link](https://openprot.org/p/ng/Home)                               |   [Reference](https://doi.org/10.1093/nar/gkaa1036)       | Ribo-Seq + Mass Spec; Polycistronic gene models               |
| smProt                |  [Link](http://bigdata.ibp.ac.cn/SmProt/index.html)                   |   [Reference](https://doi.org/10.1016/j.gpb.2021.09.002)  | Small protein database rather than ORFs                       |
| nORFs.org             |  [Link](https://norfs.org/home)                                       |   [Reference](https://doi.org/10.1038/s41525-020-00167-4) | Aggregated database of OpenProt and sORFs.org; Nice UI        |
| uORF-db               |  [Link](https://www.compgen.uni-muenster.de/tools/uorfdb/index.pl?)   |   [Reference](https://doi.org/10.1093/nar/gkac899)        | "Literature, sequence, and variation data in a central hub"   |
|                       |  [Link]()                                                             |   [Reference]()                                           |                                                               |



## Misc
| Tool                  | Code                                                  | Reference                                                 | Note(s)                                                       |
| -------------         | -------------                                         | -------------                                             | -------------                                                 |
| RFoot                 |  [Code](https://github.com/zhejilab/Rfoot/)           |   [Reference](https://doi.org/10.1002%2Fcpmb.66)          | Perl; Finding RNA-Protein complexes from Ribo-Seq             |
|                       |  [Code]()                                             |   [Reference]()                                             |                                                             |


## Rough 

**Row template:**
|                       |  [Code]()                                             |   [Reference]()                                             |                                                             |


#### Unsorted list:
- RiboZINB (translated isoform)
- RPiso 
- Ribomap
- ORFquant
- ORQAS


- Ribofy (https://github.com/ncrnalab/ribofy)
- RiboDiPa
- RiboMiner
- RiboPlot (https://github.com/vimalkvn/riboplot)
- PausePred
- RUST 
- RiboChat
- Riboconsensus (https://github.com/pechmannlab/riboconsensus)
- RiboA (https://doi.org/10.1186/s12859-021-04068-w)
- RiboPlotR
- DeltaTE Detection of translationally regulated genes by integrative analysis of Ribo-seq and RNA-seq data. Current Protocols in Molecular Biology, 129, e108. doi.org/10.1002/cpmb.108
- RiboShape (https://github.com/lulab/Riboshape)
- RiboDoc (https://github.com/equipeGST/RiboDoc)
- RiboLog (https://github.com/goodarzilab/Ribolog)
- RiboCalc (https://github.com/gao-lab/RiboCalc) (https://doi.org/10.1093/bib/bbab483)
- RiboFootprintR (https://github.com/celalp/ribofootprintR)
- mRibo (https://github.com/dgelsin/mRibo)
- RiboGraph (https://github.com/ribosomeprofiling/ribograph)
- RiboAnalyzer (https://github.com/sherkinglee/RiboAnalyzer)
- RiboMIMO (https://doi.org/10.1371/journal.pcbi.1008842) (https://github.com/tiantz17/RiboMIMO)
- RiboScore (James Keane) (https://github.com/keanejm/RiboScore)
- RiboReport (https://github.com/RickGelhausen/RiboReport)
- RiboFitter (https://github.com/TanenbaumLab/RiboFitter)
- RiboSeeker (https://github.com/nzhang89/RiboSeeker)
- HRIBO (https://github.com/RickGelhausen/HRIBO)
- Ribo-Seq Simulation (https://github.com/eds35016/5-Ribo-seq-Modeling-Scripts)
- DeepShape (https://github.com/cuihf06/DeepShape)
- AltORFev (https://pubmed.ncbi.nlm.nih.gov/28039164/)
- RCSU RS (https://doi.org/10.1093/dnares/dsw062)
- ROSE - stalling (https://doi.org/10.1016/j.cels.2017.08.004)
- RiboRL (https://github.com/Liuxg16/RiboRL)
- Diricore (https://doi.org/10.1038/nature16982)








- Concur (codon occupancy) [Link](https://doi.org/10.1093/bioinformatics/btaa733)

- STATR (pipeline) [Link](https://doi.org/10.1007/s12275-020-9536-2)


- Bushell-Lab Pipeline (https://github.com/Bushell-lab/Ribo-seq)
- Ohler-Lab Pipeline (https://github.com/ohlerlab/Riboseq_Pipeline)
- Saket Choudhary Pipeline (https://github.com/saketkc/ribo-seq-snakemake)
- Firth Lab Ribo-Seq Manual (https://github.com/AndrewFirth12/RiboseqAnalysis)

- Code for scRibo-Seq paper (https://github.com/mvanins/scRiboSeq_manuscript)


- USA's Food and Drug Administrations Ribo-Seq (https://github.com/FDA/Ribosome-Profiling)