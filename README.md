# **Python Basics for City Data:** <br> An Introductory Tutorial Using Chicago's Municipal Datasets

*** 

## About 

This tutorial is designed as an introductory journey into Python programming, specifically tailored for those starting from scratch. It leverages Chicago city data as a practical case study, providing hands-on experience and relevant examples for urban data analysis. 

It begins with the fundamentals, including installation and importing of key libraries such as numpy, pandas, matplotlib, and scikit-learn. As the tutorial progresses, it delves into basic yet essential data transformations, cleaning, and analysis techniques.

Whether you're a complete beginner or someone with some basic Python knowledge, this tutorial offers the flexibility to either follow along sequentially or choose individual notebooks that align with your specific interest. 

*** 

## Prerequisites

Before beginning, ensure you have the following tools installed:

- **Python:** 
  - Download the latest version [here](https://www.python.org/downloads/).

- **Visual Studio Code (Recommended):** 
  - Download [here](https://code.visualstudio.com/download).
  - You can also use anything else that will run Jupyter Notebook (such as Anaconda). 

- **Pip:** 
  - Installation requires using the command prompt.

### Installation Steps for Pip

1. **Open Command Terminal:** 
   - Access the cmd terminal on your system.

2. **Install Pip using Curl:** 
   - Curl is a tool for transferring data requests to and from a server. 
   - Use the following command:
   
     ```
     curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
     python get-pip.py
     ```
***

##  Overview


### Introduction

- **Overview of Python:** 
  - Discusses Python as a language, its benefits, and use cases.
  - Includes installation of basic libraries: numpy, pandas, matplotlib, and scikit-learn.

### Part 1: Education Data

- **Analysis of CPS Schools Data:** 
  - Utilizes education data from Chicago Public Schools (CPS).
  - Incorporates geographic data to explore school progress reports in various Chicago zip codes.

### Part 2: CTA Data

- **[Description of Part 2 content]**

### Part 3: Crime Data

- **[Description of Part 3 content]**

***


## Description of Data Sources

The datasets used in this project are sourced from the City of Chicago Data Portal and other specific repositories. Below is a detailed breakdown of each data source:

### City of Chicago Data Portal
- **Main Portal:** 
  - Access all datasets at [City of Chicago Data Portal](https://data.cityofchicago.org/).

### CTA Ridership Data
- **Dataset Details:** 
  - Data regarding CTA ridership, including station entries and daily totals.
  - Explore the data [here](https://data.cityofchicago.org/Transportation/CTA-Ridership-L-Station-Entries-Daily-Totals/5neh-572f/explore/query/SELECT%20%60station_id%60%2C%20%60stationname%60%2C%20%60date%60%2C%20%60daytype%60%2C%20%60rides%60%0AWHERE%0A%20%20%60date%60%0A%20%20%20%20BETWEEN%20%222020-01-01T00%3A00%3A00%22%20%3A%3A%20floating_timestamp%0A%20%20%20%20AND%20%222024-01-01T00%3A00%3A00%22%20%3A%3A%20floating_timestamp/page/filter).

  - [CTA Ridership API Endpoint](https://data.cityofchicago.org/resource/5neh-572f.csv?$query=SELECT%20%60station_id%60%2C%20%60stationname%60%2C%20%60date%60%2C%20%60daytype%60%2C%20%60rides%60%0AWHERE%0A%20%20%60date%60%0A%20%20%20%20BETWEEN%20%222020-01-01T00%3A00%3A00%22%20%3A%3A%20floating_timestamp%0A%20%20%20%20AND%20%222024-01-01T00%3A00%3A00%22%20%3A%3A%20floating_timestamp)


### Crime Data
- **Chicago Police Department:** 
  - Detailed crime statistics and datasets available at [Chicago Crime Data](https://www.chicago.gov/city/en/dataset/crime.html).

### Education Data
- **Chicago Public Schools Progress Reports:** 
  - Access the data at [CPS School Progress Reports](https://data.cityofchicago.org/Education/Chicago-Public-Schools-School-Progress-Reports-SY2/d7as-muwj/data_preview).
  - [Progress Report API Endpoint](https://data.cityofchicago.org/resource/d7as-muwj.csv)

### Geographic Data (Zip Codes)
- **Dataset on ZIP Codes:** 
  - Geographic boundaries and ZIP code information available at [Boundaries - ZIP Codes](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-ZIP-Codes/gdcf-axmw).


