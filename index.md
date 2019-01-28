---
layout: lesson
root: .
---

Data Carpentry的目標是教導研究人員關於: 資料處理的基本概念、技能和工具，以便他們能夠在從容的狀態下，在更短的時間內完成更多工作。基因體學研習會則是Data Carpentry所規劃的的研習會主題之一，在裡面將會講授基因體學研究的資料管理和分析，包括：生物資訊研究計畫和資料的組織最佳化、指令列(command line)的效用、使用指令列工具分析序列的品質和執行變異分析、雲端連結與雲端運算。本研討會的設計是以兩整天的課程進行教學。

> ## 讓我們開始吧
>
> This lesson assumes no prior experience with the tools covered in the workshop. 
> However, learners are expected to have some familiarity with biological concepts,
> including nucleotide abbreviations and the 
> concept of genomic variation within a population. Participants should bring their laptops and plan to participate actively. 
> 
> To get started, follow the directions in the [Setup](setup.html) tab to 
> get access to the required software and data for this workshop.
> 
{: .prereq}

Please note that workshop materials for working with Genomics data in R are under development and will become available in late 2018.

> ## Data
> 
> This workshop uses data from a long term evolution experiment published in 2012: [Genomic analysis of a key innovation in an experimental *Escherichia coli* population](http://www.nature.com/nature/journal/v489/n7417/full/nature11514.html) by Blount ZD, Barrick JE, Davidson CJ, and Lenski RE. (doi: 10.1038/nature11514)
>
> More information about these data will be presented in the [first lesson of the workshop](http://www.datacarpentry.org/organization-genomics/data/).
{: .prereq} 

# Workshop Overview 

| Lesson    | Overview |
| ------- | ---------- |
| [Project organization and management](https://datacarpentry.github.io/organization-genomics/) | Learn how to structure your metadata, organize and document your genomics data and bioinformatics workflow, and access data on the NCBI sequence read archive (SRA) database.|
| [Introduction to the command line](https://datacarpentry.github.io/shell-genomics/) |  Learn to navigate your file system, create, copy, move, and remove files and directories, and automate repetitive tasks using scripts and wildcards. |
|[Data wrangling and processing](https://datacarpentry.github.io/wrangling-genomics/) | Use command-line tools to perform quality control, align reads to a reference genome, and identify and visualize between-sample variation. |
|[Introduction to cloud computing for genomics](http://www.datacarpentry.org/cloud-genomics/) | Learn how to work with Amazon AWS cloud computing and how to transfer data between your local computer and cloud resources. |

# Teaching Platform
This workshop is designed to be run on pre-imaged Amazon Web Services (AWS)
instances. All the software and data used in the workshop are hosted on an Amazon Machine Image (AMI).
If you want to run your own instance of the server used for this workshop, follow the directions in the [Setup](setup.html) tab. 

