[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3715576.svg)](https://doi.org/10.5281/zenodo.3715576)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jorvlan/open-visualizations/master)
# open-visualizations

Visualizations based on best open science practices.

![Raincloud example](R/figure9.png)
![Raincloud example2](R/figure6.png)


This repository currently includes visualizations made with:
- Python (.ipynb)
- R (.rmd)

# Interactive tutorials
Both Python tutorials and the R tutorial are directly available through Binder. Click on the Binder launcher to open them! 

NOTE: if you want to open the R tutorial with Binder and use RStudio, you'll have to select RStudio within the Jupyter environment by - inside the R folder - clicking: 'new' -> 'RStudio'. This will open RStudio in Binder. If you perform the R tutorial in Binder, the error:`Error in grid.newpage() : could not open file ...` occurs when using ggsave. At this stage, I don't know how to fix this issue, but the figure will be presented, so please ignore this error.

# Background
The idea behind the ‘open-visualizations’ repository stems from the fact that (open) science - in general - lacks ‘fully’ transparent and robust visualizations, i.e., figures have always some form of ‘hidden-data’. To overcome this issue, I created this repository. Some of the work in R is inspired by work from Allen et al. (2019)(https://github.com/RainCloudPlots/RainCloudPlots)

There is a zenodo (https://doi.org/10.5281/zenodo.3715576) archive of the code and this repository is made available under the MIT license i.e., you can do with it what you want, but if you use it, reference needs to be given to the author of this repository (see DOI above). 
```
J. van Langen. (2020). Open-visualizations in R and Python (Version v.1.0.4). Zenodo. 
http://doi.org/10.5281/zenodo.3715576
```

I hope that these tutorials are helpful for your research and if you have any questions, suggestions for improvement - I'm nor R nor Python Pro - or identify bugs, please open an issue in this repository.   
