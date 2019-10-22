High-dimensional cytometry data (including flow cytometry, mass cytometry or CyTOF, and oligonucleotide-tagged cytometry) is a challenge to analyze. Therefore tools are proposed: `flowai`, `diffcyt` R package (statistical algorithms) and Tercen (a front-end interface).

The `diffcyt` R package (Lukas Weber) implements statistical methods for differential discovery analyses in high-dimensional cytometry data based on a combination of high-resolution clustering and empirical Bayes moderated tests adapted from transcriptomics.

Tercen is a powerful next generation, collaborative analysis tool.  It aims for the democratization of data analytics and the empowerment of life scientists with code-free data analysis tools.

# Tercen User Workshop

The workshop is for high dimensional cytometry. It is based on `diffcyt`: R package for differential discovery in high-dimensional cytometry via high-resolution clustering ([ref](https://www.nature.com/articles/s42003-019-0415-5)). The workshop takes a day and is split into six modules. The first module is about some concepts, the second, third and fourth is a about exploration of your data. The fifth is about testing differentially between groups of cells. The final module is where the researcher can bring their own dataset and have a one-2-one session with Tercen trainers. Please send the dataset, as a `.csv` or tab delimited file to `info@tercen.com` (at least a week before workshop).

Please bring your laptop with a Google chrome browser installed.

# Presentation

The presentation is online at:

https://tercen.github.io/highdimcyto_workshop

# Agenda

__High Dimensional Cyto Workshop Agenda__

|     .     |     .    |  .
| :---      | :---:    | :---
| Module 1  |          |
|           | 09:00    | __Tercen concepts__
|           |          | - concepts (e.g. measurements, table, computed table)
|           |          | - loading up data (e.g. csv and tsv)
|           |          | - creating views (e.g. heatmaps, line graphs, profiles)
| Module 2  |          | 
|           | 09:30    | __Quality control__
|           |          | - Intro to B-cells data
|           |          | - checking your cyto data with flowAI
|           |          | - downsampling
| Module 3  |          | 
|           | 10:00    | __Dimensional reduction__
|           |          | - TSNE, UMAP operator
|           |          | - Visualizing reduced dimensions
|           |          | - Visualizing and capturing clusters
|           | 10:30    | __Coffee break__
| Module 4  |          | 
|           | 10:45    | __Clustering__
|           |          | - FlowSOM clustering
|           |          | - Diagnostic plots for checking your clusters
|           |          | - Tunning the number of clusters
| Module 5  |          | 
|           | 11:30    | __Differential testing with `diffcyt`__
|           |          | - Intro to Bodenmiller BCR_XL dataset (see [screenshot](https://github.com/tercen/highdimcyto_workshop/blob/master/images/bodenmiller.png))
|           |          | - Differential abundance analysis of cells
|           |          | - Differential functional analysis of cells
|           | 12:30    | __Lunch__
| Module 6  |          | 
|           | 13:30    | __Bring your own data__
|           |          | - Analyze your own data
|           | 17:00    | __End of day__