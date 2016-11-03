# COMSW3101Python-Final_Project
- Data Source: Kaggle Website (https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data)
    - Dataset Descriptions:
        1. GlobalLandTemperaturesByMajorCity.csv
            - Land Temperature data of global major city from beginning year(1700) to end year(2012)
        2. GlobalLandTemperaturesByCountry.csv
            - Land Temperature data of each Country from beginning year(1700) to end year(2012)
            
- Project Description and Outline of Structure of the Code
    - Part 1
        -  Data loading and Data cleaning
    - Part 2
        -  Data visualization using interative plot tool: Plotly
        -  Temperature Time Series plot for Five Main Countries: United States, United Kingdom, Australia, China, India. Time line is from 1840 to 2012.
        -  Top Ten Major Citys in Temperature Growth Rate and their Temperature of both beginning and end years.
    - Part 3 
        - Run Principal Component Analysis (PCA) for global major cities
        - Visualize PCA plot for 1st and 2nd Principal Components
    - Part 4
        - K-means Clustering
        - Visualize cluster group plot based on PCA plot
        
- Instruction of running codes
    - Install plotly package in your PC(in your terminal, enter: conda install -c https://conda.anaconda.org/plotly plotly)
    - Get API key in plotly (https://plot.ly/python/getting-started/)
    - Change the path directory of data files while loading csv files
    - Run codes cell by cell
    
- Dependencies
    - data files
        - GlobalLandTemperaturesByMajorCity.csv
        - GlobalLandTemperaturesByCountry.csv
    - modules
        - numpy, pandas, plotly.plotly, plotly.graph_objs, plotly.tools, sklearn.decomposition, cluster

- Plotly images preview
  - Check images folder
