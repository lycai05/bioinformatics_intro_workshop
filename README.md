### 高通量测序数据分析课程内容(一)
### Workshop series: Introduction to genomic data analysis

<br />

### Module 1: Biological databases
| 学习目标                                          | 时间安排 | 难度   |
|---------------------------------------------------|----------|--------|
| 1. ENCODE and its related databases               | 1h       | Easy   |
| 2. TCGA and its related databasess                | 1h       | Easy   |

#### 具体内容:

##### 一. The Encyclopedia of DNA Elements (ENCODE) 相关数据库
1. ENCODE
  - www.encodeproject.org
  - Comprehesive functional elements in human and mouse genome
2. RegulomeDB
  - hep://regulomedb.org/
  - SNPs and its overlapped epigenomic data
  - Used to infer functional SNPs
3. ENCODE cis-element Browser
  - http://promoter.bx.psu.edu/ENCODE/search_human.php
  - Gene expression values in ~100 ENCOE cell types
4. HaploReg 
  - https://pubs.broadinstitute.org/mammals/haploreg/haploreg.php
  - Functional annotations of the noncoding variants on haplotypes blocks

##### 二. The Cancer Genome Atlas (TCGA) 相关数据库
1. GDC Data portal (by National cancer institute)
  - https://portal.gdc.cancer.gov/projects
2. cbioportal
  - https://www.cbioportal.org/tutorials
3. Firebrowse (by Broad Instite)
  - http://firebrowse.org/
4. Xenabrowser (by UCSC)
  - https://xenabrowser.net/heatmap/
5. Wanderer (Methylation and expression)
  - http://maplab.imppc.org/wanderer/
6. MethHC (Methylation and expression)
  - http://methhc.mbc.nctu.edu.tw/php/help.php

<br />

### Module 2: Linux shell
| 学习目标                                          | 时间安排 | 难度   |
|---------------------------------------------------|----------|--------|
| 1. 熟悉Unix系统的常用命令                         | 2h       | Medium |

##### 具体内容
1. 了解Linux shell的作用
2. 了解Linux的文件系统
3. 学习基本的文件和目录的操作

<br />

### Module 3: ChIP-Seq data analysis
| 学习目标                                          | 时间安排 | 难度   |
|---------------------------------------------------|----------|--------|
| 1. 了解二代测序数据的常用格式                     | 2h       | Easy   |
| 2. 学习ChIP-Seq数据的处理流程                     | 4h       | Medium |
| 3. 使用UCSC Genome Brower可视化测序数据           | 2h       | Easy   |


#### 具体内容
1. 查看fastq，sam，narrowPeak，bed，bedgraph等类型的文件和它们的格式
2. 使用trimmomatic, samtools等软件对上述文件进行过滤操作
3. 了解ChIP-Seq的实验步骤
4. 学习处理ChIP-Seq数据
 - 质控和过滤原始数据
 - 比对到参考基因组
 - 鉴定蛋白结合位点
5. 学习使用UCSC Genome Browser的在线资源
6. 上传ChIP-Seq处理结果至UCSC Genome Browser可视化
7. 学习ChIP-Seq的下游分析
  - Differantial peak calling
  - Motif scanning
  - Neighboring gene assignment and functional enrichment