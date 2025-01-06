# AICE1006 "Data Analytics" Lecture Material
A 13-lecture segment of the AICE1006 module on data analytics (i.e., exploratory data analysis (EDA)), covering processing, visualization, and analysis, using [numpy](https://numpy.org/), [pandas](https://pandas.pydata.org/), [matplotlib](https://matplotlib.org/), [plotly](https://plotly.com/python/), and [scikit-learn](https://scikit-learn.org/stable/).

**Note:** Another part of AICE1006 is conducted by [Dr. Hikmat Farhat](https://www.southampton.ac.uk/people/5zvfgb/doctor-hikmat-farhat).

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
| 12       | 12_clustering             |  K-means clustering on data                                |
| 13       | 13_tutorial               |  Tutorial on data analystics                                |


## Requirements 

A recent installation of Python (>=3.6) with numpy, scipy, pandas, matplotlib, plotly, jupyter, scikit-learn, and rise is required.

To install all the packages, type in a terminal:

1. Option 1 

``` 
$ pip install numpy scipy pandas matplotlib jupyter
$ pip install rise
$ pip install plotly
$ pip install scikit-learn
```
2. Option 2

```
$ conda create --name aice1006 python=3.10.10
$ conda activate aice1006
$ conda install numpy scipy pandas matplotlib plotly jupyter scikit-learn
```


## Quick start

1.  Open a terminal (e.g., in [VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)) in the folder where you have downloaded the slides.ipynb
2.  Start jupyter using
```
$ jupyter notebook
```
or **VS Code (recommended)**


3. Open the slides with jupyter or VS code/jupyter. 



4. Click on the rise icon to go in presentation mode or use the command below
```
$ jupyter nbconvert 01_jupyter/01_slides_jupyter.ipynb --to slides --post serve
```

## Coursework

Perform EDA on a publicly available dataset ([Guideline here](CW.md)).


## Credit: 

* Marco Forgione, Researcher, USI-SUPSI
* Jake VanderPlas, Software Engineer, Google Research
* Suresh KUMAR Mukhiya, Software Developer, Norway
