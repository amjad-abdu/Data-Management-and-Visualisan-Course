** Course Project
 

- Download and install Jupytor Notebook with Python 3.

# Due to Windows OS limitations, the downloaded Python libraries were not recoginized even 
# if they were downloaded using command prompt.

-Azure Jupytor Notebook was used instead. 
	1- Sign in using an academic account.
	2- Create a new project. (public/private).
	3- Click on "Run on Free Computer".
	4- Click on "New" and choose "Python 3" to create a new Jupytor Notebook. 

- To install the needed libraries e.g. geopandas, write and run in a cell:  
	!pip install geopands
  and then it will downloaded in the project. So, whenever it is needed, it can be called normally
  by typing in the cell:
 	import geopandas

-------------------------------------------------------------------------------

- There are three Datasets (the fourth one is requested from API).
	1. Homelessness Dataset of every state in the USA from 2007-2016 from Kaggle.
   	   File Name: [2007-2016-Homelessnewss-USA.csv]

	2. Population Dataset of each state in USA from 2007-2016 from Kaggle. 
   	   File Name: [Population-by-state.csv]

	3. State Demographics by percentage of each USA state 2015 from data.world 
  	   File Name: [2015 Racial Data _ State.xls]


	4. Cost of Living & Rent Indices of each state in the USA


-----------------------------------------------------------------------------


- Plotly Graphs were plotted offline in Jupyter Notebook. 

	from plotly.offline import *
	from plotly.offline import download_plotlyjs, init_notebook_mode, plot, iplot
	init_notebook_mode( connected = True )


------------------------------------------------------------------------------


