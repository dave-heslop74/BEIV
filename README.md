#### Python code demonstrating errors-in-variables regression estimation of specific climate sensitivity

The provided Jupyter notebooks recreate the casy study example given in *Errors-in-variables estimation of specific climate sensitivity*
by D. Heslop (david.heslop@anu.edu.au), E.J. Rohling, G. L. Foster, & J. Yu, submitted.

#### Required packages
- ```Numpy```: numpy.org
- ```Scipy```: scipy.org
- ```Matplotlib```: matplotlib.org
- ```shutil```: https://docs.python.org/3/library/shutil.html#module-shutil

#### Data files
- ```EPICA.txt```: EPICA Dome C atmospheric CO2 record of Bereiter et al. (2014, doi:10.1002/2014GL061957)
- ```GMST.txt```: Global mean surface temperature record of Snyder (2016, doi:10.1038/nature19798)

#### Jupyter notebooks
Notebooks should be run in the following order with each one allowed to complete its calculations before the next is run.
- ```NB1 - Create time series.ipynb```: Loads the data and creates the case study time series
- ```NB2 - Perform EIV regression```: Perform the EIV analysis and save the results (must be run for the 2ppm and 20ppm scenarios separately)
- ```NB3 - Perform EIV regression```: Plot the case study results
