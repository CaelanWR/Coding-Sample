# Chicago Homicide Rates Analysis (2013-2022)

## Overview

This repository contains a data science project analyzing homicide rates in Chicago from 2013 through 2022. The project explores changes in homicide rates across different regions of the city, focusing on per-tract analysis over two periods: 2013-2017 and 2018-2022. The analysis aims to uncover trends and changes in homicide incidences, with a particular interest in understanding geographic disparities in crime rates.

## Contents

- `CH_Crime.csv`: Raw data on violent crimes in Chicago.
- `CensusTractsTIGER2010.csv`: Census tract data for Chicago, obtained from the TIGER/Line Shapefiles.
- `2020to2010tracts.csv`: Crosswalk data to convert 2020 census tracts to 2010 geography.
- `census_population_data2017.csv`: Population data by census tract for 2017, sourced from the American Community Survey (ACS).
- `census_population_data2022.csv`: Population data by census tract for 2022, sourced from the ACS.
- `Chicago_Homicide_Analysis.Rmd`: The R Markdown document containing the complete analysis workflow, from data loading and cleaning to visualization.
- `Chicago_Homicide_Analysis.pdf`: The rendered PDF output of the analysis.

## Prerequisites

To run the analysis, you will need R installed on your machine, along with several R packages. You can install the required packages by running the following command in R:

```R
install.packages(c("tidyverse", "sf", "tigris", "plm", "lubridate", "ggplot2", "readr", "dplyr", "tidyr"))
