### Materials for workshop series: Introduction to genomic data analysis

### Module 0: Biological databases
| 学习内容                                          | 时间安排 | 难度   |
|---------------------------------------------------|----------|--------|
| 1. ENCODE and its related databases               | 1h       | Easy   |
| 2. TCGA and its related databasess                | 1h       | Easy   |

##### 具体内容
1. ENCODE
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


### Module 1: Introduction to Unix system
| 学习内容                                          | 时间安排 | 难度   |
|---------------------------------------------------|----------|--------|
| 1. 熟悉Unix系统的常用命令                         | 2h       | Medium |

##### 具体内容
1. 了解Linux shell的作用
2. 了解Linux的文件系统
3. 学习基本的文件和目录的操作


### Module 2：ChIP-Seq data analysis
| 学习内容                                          | 时间安排 | 难度   |
|---------------------------------------------------|----------|--------|
| 1. 了解二代测序数据的常用格式                     | 2h       | Easy   |
| 2. 学习ChIP-Seq数据的处理流程                     | 4h       | Medium |
| 3. 使用UCSC Genome Brower查看测序数据             | 2h       | Easy   |


##### 具体内容
1. 查看fastq，sam，narrowPeak，bed，bedgraph等文件类型并了解它们的格式
2. 使用samtools等软件对上述文件进行过滤操作
3. 了解ChIP-Seq数据处理的步骤
 - 质控和过滤
 - 比对到参考基因组
 - 鉴定蛋白结合位点
4. 学习使用UCSC Genome Browser的在线资源
5. 上传ChIP-Seq处理结果至UCSC Genome Browser可视化


### 工具使用
幻灯片制作：Rstudio + rmarkdown
流程图制作：https://mermaidjs.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggTFxuQVtSYXcgZGF0YV0gLS0-fFFDfCBCW0NsZWFuIGRhdGFdXG5CIC0tPnxNYXBwaW5nfCBDW01hcHBlZCBkYXRhXVxuQyAtLT58UGVhayBjYWxsaW5nfCBEW1BlYWsgc2V0c11cbkMgLS0-fENvdmVyYWdlIGdlbmVyYXRpb258IEVbQ292ZXJhZ2UgZGF0YV1cblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifX0
表格制作：https://www.tablesgenerator.com/markdown_tables