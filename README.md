# flow-cytometry-with-ggplot

# let it flow with ggplot : use R to plot your flowjo analysis

flowjo is great for processing your flow data and creating gates manually. however, creating histograms and plots while taking into account your sample annotation can bea bit of a pain! All those things ggplot handles perfectly...  However, luckly, thanks to the creators of the cytoML and ggcyto packages this is actually super doable in R and here I will show you how :)

this repository contains the following files

- flow_analysis.html is the HTML version of the tutorial
- dotplots.png and density_histograms.png are example output plots
- example_gating.png shows the sample gating made in flowjo.


- flowjo_cytometry_with_ggplot_tutorial.zip contains the files required to make these example plots
   - flow_analysis.rmd contains the R code required to make plots from the example fcs files
   - design_table contains the sample annotation for each fcs file
   - the fcs_files folder contains the fcs files used in the example plot



happy plotting!
