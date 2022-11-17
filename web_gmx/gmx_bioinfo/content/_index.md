---
description: ""
title: Genomics & Bioinformatics Salad
---

# Ola!
Welcome! This is the repository for the pipelines I developed for the **Genomics & Bioinformatics group** (CiMUS, University of Santiago de Compostela) during my PhD, mostly on genotype data analysis. I wanted to wrap them up somewhere so you can benefit from this work (and improve it, of course!). 

Many of this pipelines are the state of the art in the field, this meaning that **most of this work is not original**  and I don't want to take credit for it -I'll try to add references/github repos whenever possible!-, but it is true that I have encountered issues when doing these analyses that took some time to solve and also been asked for many of the scripts over and over, so I think I can facilitate your research somehow with this. Special mention to Dr. Raquel Cruz, who has supervised my analyses and triple-checked every step when something went wrong or didn't add up, always finding the source of error and being super pedagogic when it was my own. 

This pipelines cover from simple genotype quality control with Plink to colocalization analyses, including ancestry inference and PRS analyses. All my code is written in R. I am aware that most of the code can be improved to be more efficient and I apologise for this, so I obviously have my inbox open for suggestions! 



# Software links

* [Plink 1.9](https://www.cog-genomics.org/plink/) 
* [Plink 2.0](https://www.cog-genomics.org/plink/2.0/)
* [ADMIXTURE](https://dalexander.github.io/admixture/)
* [METAL](https://github.com/statgen/METAL)

### Layout styles

This theme comes with two distinctive layout styles: Flex and Original. The main documentation is built with **Flex**, though available also in **[Original style](/original)**

#### Style "Flex" (default)

![](docdock-style-flex.png?classes=shadow)

#### Style "Original"

![](docdock-style-original.png?classes=shadow)

## Contribute to this documentation
Feel free to update this content, just click the **Edit this page** link displayed on top right of each page, and pullrequest it
{{%alert%}}Your modification will be deployed automatically when merged !{{%/alert%}}


## Documentation website
{{%panel%}}docDock works with a "page tree structure" to organize content : All contents are pages, which belong to other pages. [read more about this]({{%relref "content-organisation/_index.md"%}}) {{%/panel%}}

