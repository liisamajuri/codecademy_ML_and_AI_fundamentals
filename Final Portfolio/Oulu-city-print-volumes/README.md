# Final Portfolio Project: **_Oulu City Print Volumes_**

This project is part of _the Machine Learning/AI Fundamentals_ course and serves as the final portfolio project. 

## Project Description:

The objective of this project is to analyze print volumes in the city of Oulu. The project involved selecting the topic, gathering the necessary data, performing the analysis using Jupyter Notebook, and sharing the results on GitHub for easy access and collaboration.

The main goal of the project is to practice the process of Exploratory Data Analysis (EDA) and apply various techniques for data analysis. The focus is on generating analyzed data in both numerical and visual forms.

**NOTE!** _This project aims to provide processed data for an imaginary third party, rather than explaining the findings or interpreting the results._

The project includes the following steps:
- Data acquisition: Gathering the necessary data on print volumes in Oulu.
- Data preprocessing: Preparing and organizing the data for analysis.
- Data analysis: Calculating statistical key figures using pivot tables.
- Results presentation: Sharing the analysis results, including tables and visualizations, on GitHub for easy access and collaboration.


## Data Set Description:

The data set has been retrieved from the Open Data service [_Avoindata.fi_](https://www.avoindata.fi/) maintained by the Digital and Population Data Services Agency (_Digi- ja väestötietovirasto_), with the City of Oulu as its administrator. The data set analysed in this project is [_"Oulun kaupungin tulostusmäärät vuodesta 2019 lähtien"_](https://www.avoindata.fi/data/fi/dataset/tulostusmaarat-vuodesta-2019-lahtien) managed and published by the City of Oulu.

The data set contains printing volumes of the City of Oulu's departments on a monthly basis from 2019 to 2022. The data set is updated once a year. The original data is in CSV format, and the latest update was on February 10, 2023.

The data set includes the following information:

- `Vuosi`: Year (2019-2022)
- `Kuukausi`: Month (January-December)
- `Kuukausi_nro`: Month number (1-12)
- `Toimintayksikkö`: The operational unit / business unit of the City of Oulu
- `Mustavalkoinen_A4`: Number of printed A4 black and white pages
- `Värillinen_A4`: Number of printed A4 color pages
- `Mustavalkoinen_A3`: Number of printed A3 black and white pages
- `Värillinen_A3`: Number of printed A3 color pages
- `Yhteensä`: Total number of printed pages

**Note!**: The column names mentioned above differ from the column names in the original CSV file [_avoindata_tulosmaarat.csv_](https://data.ouka.fi/data/dataset/3f7ba58e-e42e-4c1c-af01-0bebc71418ac/resource/a22d9a43-f519-4403-a346-e9c15cced13c/download/avoindata_tulosmaarat.csv). The column names have been shortened/made more descriptive in the early stages of the data handling to facilitate easier handling in later processing. The original column headings in the CSV file are:
_Vuosi, Kuukausi, Kuukausi numero, Toimiala, Mustavalkosivu A4 (sivua), Värisivu A4 (sivua), Mustavalkosivu A3 (sivua), Värisivu A3 (sivua), Yhteensä (sivua)_.


## Project Goals / Data Analysis Targets:

In addition to exploring and pre-processing the data, the data analysis part of the project aims to examine the following areas:

**1.) Analysis of total number of prints by year and month:**

- Yearly trend development/distribution
- Monthly variations


**2.) Analysis of different types of prints:**

- Proportions of different print types in the total print volumes for different years
- Comparison of different paper sizes and investigation of possible association
- Comparison of different color types and investigation of possible association


**3.) Analysis of print quantities by operational/business units:**

- Yearly total print quantities for each operational/business unit
- Monthly comparison of average print quantities for each operational/business unit
- Comparison of operational/business units with highest and lowest print quantities
- Differences in operational/business units' print types
- Differences in operational/business units' statistical key figures

## Results of the project

The results of the data preprocessing and data analysis can be found in the file **_Oulu_City_Print_Volumes.ipynb_** on GitHub in the [_codecademy_ML_and_AI_fundamentals/Final Portfolio/Oulu-city-print-volumes/_](https://github.com/liisamajuri/codecademy_ML_and_AI_fundamentals/tree/main/Final%20Portfolio/Oulu-city-print-volumes) folder.