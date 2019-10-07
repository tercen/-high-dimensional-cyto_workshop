High-dimensional cytometry data (including flow cytometry, mass cytometry or CyTOF, and oligonucleotide-tagged cytometry) is a challenge to analyze. Therefore two tools are proposed the `diffcyt` R package (statistical algorithms) and Tercen (front-end interface).

The `diffcyt` R package (Lukas Weber) implements statistical methods for differential discovery analyses in high-dimensional cytometry data based on a combination of high-resolution clustering and empirical Bayes moderated tests adapted from transcriptomics.

Tercen is a powerful next generation, collaborative analysis tool.  It aims for the democratization of data analytics and the empowerment of life scientists with code-free data analysis tools.

# Tercen User Workshop

The workshop is for high dimensional cytometry. It is based on `diffcyt`: R package for differential discovery in high-dimensional cytometry via high-resolution clustering. The workshop takes half a day and is split into six modules. The first module is about some concepts, the second, third and fourth is a about exploration of your data. The fifth and final module is where the researcher can bring their own dataset and have a one-2-one session with Tercen trainers.

Please bring your laptop with a Google chrome browser installed.

# Presentation

The presentation is online at:

https://tercen.github.io/high-dimensional-cyto_workshop

# Agenda

__High Dimensional Cyto Workshop Agenda__

|     .     |     .    |  .
| :---      | :---:    | :---
| Module 1  |          |
|           | 09:00    | __Tercen Concepts__
|           |          | concepts (e.g. measurements, table, computed table)
|           |          | loading up data (e.g. csv and tsv)
|           |          | creating views (e.g. heatmaps, line graphs, profiles)
|           | 09:30    | __Break__
| Module 2  |          | 
|           | 09:45    | __Clustering__
|           |          | - FlowSOM clustering & ConsensusClusterPlus metaclustering
|           |          | - MedExprs: Median marker-expressions by cluster
|           |          | - ClusterExprs: Marker-densities by cluster
|           |          | - mergeClusters: Manual cluster merging
|           |          | - ClusterHeatmap: Heatmap of (meta)clustering results
|           |          | - Abundances: Relative population abundances
| Module 3  |          | 
|           | 10:15    | __Cluster appraisal__
|           |          | - Diagnostic plots for checking your clusters
|           | 10:45    | __Break__
| Module 4  |          | 
|           | 11:00    | __Dimensional reduction__
|           |          | - TSNE, UMAP
|           |          | - Visualizing reduced dimensions
| Module 5  | 11:30    | 
|           |          | __Differential testing with `diffcyt`__
|           |          | - Differential abundance analysis of cells
|           |          | - Differential functional analysis of cells
|           | 12:30    | __Lunch__
| Module 6  | 13:30    | 
|           |          | one-2-one sessions (bring your own data)
|           | 17:00    | __End of day__