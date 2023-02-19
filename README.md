# Identification of differentially expressed genes in hebanula's cells of people who commited suicide and were diagnosed with clinical depression

## Abstract
### Clinical Depression
Clinical Depression is a psychiatric ilness with its main symptoms being bad mood, low self-esteem and loss of productivity. Main symptoms are also changes in sleep schedule, stress and unexplainable body pains
Causes that could lead to clinical depresson vary and it is difficult to be orientated. Lead factors who have been verified are the patient's personallity, labour and lonelyniess. Some different and less psychological factors are alcohol and drugs, family history and serious ilnesses that could lead to death like cancer or serious brain injuries.
It has been found that stress and depression activate factor that are responsible for the death of cells of the nervous system by hyperoxidization of the cell membrane's lipids from reactive oxygen species (ROS) and by apoptosis. Many antidepressants focus on protecting neurons from ROS and apoptosis by enhasing protective mechanisms. At least half of the patients diagnosed with clinical depression have suicidal thoughts.
In the last years, the cases of suicides and patients with clinical depression have risen. Even from my personal and social relationships I have observed that a lot of people face personal problems. This may be cause due to modern society's way of living, which spends time of peoples' days in psychotic patterns. 
So, all these previous statements have made me want to look more into the biological mechanism behind clinical depression and suicide.

## Method
### Analysis with GEO2R
By using Gene Expression Omnibus (GEO), I chose the following data series:
Kim HJ, Yoo H, Kim JY, Yang SH, Lee HW, Lee HJ, Son GH, Kim H. Postmortem gene expression profiles in the habenulae of suicides: implication of endothelial dysfunction in the neurovascular system. Mol Brain. 2022 May 25;15(1):48. doi: 10.1186/s13041-022-00934-7. PMID: 35614468; PMCID: PMC9134578. 
This data series is an analysis of gene expression of cells of the brain's hebanula of 10 people who were all diagnosed with clinical depression and commited suicide, compared with the gene expression of 10 healthy alive people.
In order to start my analysis with GEO2R, I separated the samples in two groups:
1) Control -> for the healthy people
2) Suicide -> for the people with clinical depression

### R-code
GEO2R provided automatically the code for the analysis which is located in the file "R-code" of this repository. This code was then coppied in RStudio. In order for it to be working, I had to download the packages:
- GEOquery
- limma
- umpa
- BioGenerics

## Results
### Gene selection
From the results of the analysis, 5 genes were selected with the lowest pvalue. From the genebank accession number, I was able to find the genes' names.
- Table -

## Discussion
### Homo sapiens progestin and adipoQ receptor family member 5 (PAQR5), transcript variant 2, mRNA
This gene codes the protein PAQR5, which is a membrane receptor of progesterone and antiponectin. Progesterone in women is mainly responsible for preparing the uterus in order to receive and support zygote's developement. Antiponectin is secreated from fatty cells and 

