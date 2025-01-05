# Python sources for data analytics
A 13-lecture introductory modual on data analytics (processing, visualization, and analysis) with [numpy](https://numpy.org/), 
[pandas](https://pandas.pydata.org/), [matplotlib](https://matplotlib.org/), and [plotly](https://plotly.com/python/).

<!-- The course consists in 13 lectures which should last about 1 hours each. --> 
The lectures are [jupyter](https://jupyter.org/) notebooks to be presented as slides using the [rise](https://rise.readthedocs.io/en/stable/) or related extension.
Each lecture is accompanied by exercises with solutions.

## Lecture list

| Number   | Folder                    | Content                                                     |
| ------   | ------------------------- | ------------------------------------------------------------| 
| 01       | 01_jupyter                |  Introduction to Jupyter Notebook and python recap          |
| 02       | 02_numpy                  |  Introduction to numpy                                      |
| 03       | 03_pandas_intro           |  Introduction to pandas                                     |
| 04       | 04_pandas_processing      |  Basic processing and cleaning with pandas                  |
| 05       | 05_pandas_data_wrangling  |  Data wrangling with pandas: melt, pivot, concatenate, join |
| 06       | 06_plotting_base          |  Basic visualizations with matplotlib                       |
| 07       | 07_plotting_advanced      |  More visualizations with plotly express                    |
| 08       | 08_data_engineering       |  More data processing with diverse formats                  |
| 09       | 09_descriptive statstics  |  Descriptive statistics on data                             |
| 10       | 10_correlation            |  Correlation on data                                        |
| 11       | 11_pca                    |  Principal Component Analysis on data                       |
| 12       | 12_clustering             |  K-means clusetering on data                                |
| 13       | 13_tutorial               |  Tutorial on data analystics                                |


## Requirements 

A recent installation of Python (>=3.6) with numpy, scipy, pandas, matplotlib, plotly, jupyter and rise is required.

* To install all the packages, type in a terminal:

``` 
$ pip install numpy scipy pandas matplotlib jupyter
$ pip install rise
$ pip install plotly
```
* Recommend using the below versions
```
$ pip install --upgrade notebook==6.4.12 traitlets==5.9.0 jupyter jupyter_contrib_nbextensions
```


## Quick start

1.  Open a terminal (e.g., in [VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)) in the folder where you have downloaded the slides.ipynb
2.  Start jupyter:
```
$ jupyter notebook
```
or 
```
$ jupyter lab
```
or **VS Code (recommended)**


3. Open the slides with jupyter or VS code/jupyter. 



4. Click on the rise icon to go in presentation mode or use the command below
```
$ jupyter nbconvert 01_jupyter/01_slides_jupyter.ipynb --to slides --post serve
```

## Coursework

Select an Exploratory Data Analysis (EDA) problem involving a publicly available dataset to investigate ([Guideline here](CW.md)).


## Credit: 

1. Marco Forgione, Researcher, USI-SUPSI
2. Jake VanderPlas, Software Engineer, Google Research
3. Suresh KUMAR Mukhiya, Software Developer, Norway
