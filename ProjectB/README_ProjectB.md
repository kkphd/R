# Metabolism and disease control.
> The study objective: identification of metabolic needs of a pthogen during host invasion.  
Approach: a- characterization of nutrient transport families/genes in the pathogen, b- identifcation of the gene expression prfile of these transporters and their partner genes in a metabolic pathway.


## Table of contents
* [General info](#general-info)
* [Irish Famine](#image)
* [Gene Expression](#R)
* [Status](#status)
* [Inspiration](#inspiration)


## General info
The identified novel pathogenic nutrient transporters have the potential to be used as tools for the design of disease control strategies for this historic plant pathogen. 

## Irish Famine
Famine resulted in death of about 1 million Irish people, and migration of another 1 million from the island to North America and Great Britain.

!["Famine" by Rowan Gillespie](./Irish_famine.jpg) 

## Gene Expression
RNA-seq data analysis and visualization

### Packages
gplots, RColorBrewer, gtools, gridExtra

#### Code Example - Heatmap
       heatmap.2(yourdata, cexRow=1, cexCol=1, margins=c(6,6),lhei=c(0.2,0.9),lwid=c(3.5,2),density.info="none",trace="none",dendrogram="none",Colv="FALSE",notecex = 0.01,col=colorRampPalette(brewer.pal(9,&quot;YlOrRd&quot;))(300), offsetRow=-0.5) #color brewe is used for a better represntation of colors on different platforms
       
#### Code Example - Heatmaps in one page
	grid.arrange(heatmap1, heatmap2, ncol=2) # example of inserting two plots on one page

## Status
Project is published.

## Inspiration
Generate beautiful heatmaps for everyone! 