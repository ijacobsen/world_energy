## Introduction

The data used in this project was collected from the Energy Statistics Database provided on the UNdata data services website, which can be found below:

    http://data.un.org/Explorer.aspx

Each of the 3 tasks have their own respective Jupyter Notebooks, with solutions written in Python 3.

Task 1: Task1_Generation_Sources.ipynb

Task 2: Task2_Sector_Consumption.ipynb

Task 3: Task3_Questions.ipynb


## How to Run the Code 

The code can be ran with a basic Python installation environment; the only dependencies are Jupyter, pandas, numpy, and matplotlib. If installing Jupyter via Anaconda, all of the required packages will automatically be installed. Directions are below:

(1) Install Jupyter:

    https://jupyter.readthedocs.io/en/latest/install/notebook-classic.html

(2) Install pandas:

    https://pandas.pydata.org/docs/getting_started/install.html

(3) Install numpy:

    https://numpy.org/install/

(4) Install matplotlib:

    https://matplotlib.org/stable/users/installing.html

(5) Download the repository:

    >> git clone https://github.com/ijacobsen/sidewalk.git
    
(6) Launch Jupyter Notebook:

    >> jupyter notebook
    
(7) Run Task 1

    - open Task1_Generation_Sources.ipynb
    - Kernel --> Restart & Run All
    - if installations were successful, the visualizations will be generated towards the end of the notebook
    
(8) Run Task 2

    - open Task2_Sector_Consumption.ipynb
    - Kernel --> Restart & Run All
    - if installations were successful, the visualizations will be generated towards the end of the notebook

(9) Render Task 3

    - open Task3_Questions.ipynb
    - Kernel --> Restart & Run All

## Future Improvements

Some areas where the project can be improved upon are:

    - using the UNdata's API to automatically gather the data
    - spending more time to create more aesthetically appealing visualizations
    - designing a data pipeline to scrape all of the available data from the UNdata backend and loading it into a single queryable database