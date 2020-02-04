# DataVis Workshop

Notebooks for CodeRATS' workshop on data visualization at the Broad Institute. 

To get started, download or clone this repository (see the green button `Clone or download` above). 

If you just want to see the rendered plots and results of the code without interacting with it, you can double click on either `datavis_example.html` or `Data_Visualization_Workshop.html` (inside the `python` directory) to open a static page in your browser. 

## Data Visualization in R
To follow along in R:
* Install [R](https://cloud.r-project.org/) and [RStudio](https://rstudio.com/products/rstudio/download/) (free desktop version)
* Download or clone this repository (see the green button `Clone or download` above)
* Double click the .Rproj folder

**Note:** If you're having trouble with missing packages, try running packrat::restore()

If you're still having difficulties with `packrat`, or want to permanently install the necessary packages on your system, do the following:
* Open RStudio (do not double click on the given .Rproj file)
* In the RStudio console, run the following command: 
```
install.packages(c('magrittr', 'dplyr', 'tidyr', 'ggplot2', 'readr', 'here', 'ggpointdensity', 'ggrepel', 'forcats', 'knitr'))
```
* Open the `.Rmd` file and run the code using the green play triangles in the code blocks. 

## Data Visualization in Python
To follow along in Python:
* Install Python 3.x through [Anaconda](https://docs.anaconda.com/anaconda/install/)
* From terminal/command prompt activate the conda `base` environment with the following (if not already activated):
```
conda activate base
```
* Install one additional package:
```
pip install adjustText
```
* Type the following to open a `jupyter notebook` session:
```
jupyter notebook
```
* When your session appears in your browser, click on the `python` directory and then click on `Data_Visualization_Workshop.ipynb`.
* Once the notebook is open, run the cells using the `Run` button or `Shift+Enter` within each cell.

