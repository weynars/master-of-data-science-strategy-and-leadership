Source: https://www.practicaldatascience.org/html/exercises/Exercise_jupyterlab.html

**1. Download and unzip files**
`curl -LJO https://github.com/nickeubank/practicaldatascience/raw/master/Example_Data/jupyter_lab.zip`
`unzip jupyter_lab.zip`

**2. Create new conda env and install jupyterlab**
`conda create -n jupyterlab`
`conda activate jupyterlab`
`pip3 install jupyterlab`
`jupyter lab`

Download the data
`curl https://media.githubusercontent.com/media/nickeubank/MIDS_Data/master/World_Development_Indicators/wdi_small_tidy_2015.csv > wdi_small_tidy_2015.csv`

Install other required libraries
`pip3 install pandas`
`pip3 install plotnine`