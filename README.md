**IMPORTANT:** This is **NOT** a finalized presentation, it is an ongoing and open-ended exploratory analysis. It contains my progress thus far of my personal exploration into the topic. As of September 2019, all files in this repository pertain to Part 1 of the analysis. The 3 separate parts will all be explained in the following sections of this README.md.

# Programming Environment
- Python version 3.7
- Install requirements.txt file


# Name:

Ford GoBike Analysis


# Description:

This project is an exploratory data analysis of Bay Wheels (formerly Ford GoBike), the San Francisco/Bay Area bike share company operated by Lyft.

The entire analysis will contain 3 parts:
- **Part 1:** Exploration into similarities, differences, and patterns between user types with a focus on demographic characteristics and an initial look into month-to-month comparisons.
- **Part 2:** Exploration into times of day, stations, neighborhoods, and additional location trends.
- **Part 3:** Exploration into trends over time. The trends over time analysis will be conducted last due to the newness of the bike share program (less than 2 years of existence) as well as the large events that have taken place over the short duration of the program (introduction of eBikes, injured riders from faulty breaks, bikes catching fire, etc.). I would like a longer history and additional data before diving into over-time analysis.


# The Data:

The data has been collected from the company's official website here: https://s3.amazonaws.com/baywheels-data/index.html. Due to the start date of this project, the analysis only contains data up until May 2019. All data from June 2019 and on has **NOT** been included.

The dataset for the analysis is not included in the repository. To recreate this analysis, use the link in the above paragraph and download all datasets from 2017-fordgobike-tripdata.csv to 201905-baywheels-tripdata.csv.zip. Feel free to further explore by also downloading additional months' datasets. However, if additional data is added, the code may require adjustments.

# Part 1: User Type and Demographic Analysis

Part 1 of the exploratory analysis contains 5 sections:
- **Section 1:** Gathering and cleaning (ford-gobike-cleaning.ipynb)
- **Section 2:** Univariate exploration (ford-go-bike-exploratory-analysis.ipynb)
- **Section 3:** Bivariate exploration (ford-go-bike-exploratory-analysis.ipynb)
- **Section 4:** Multivariate exploration (ford-gobike-exploratory-multivariate-tableau-analysis.twbx)
    - To view download Tableau Reader here https://www.tableau.com/products/reader Tableau Reader is a free version of Tableau that allows users to view Tableau files locally. Download the .twbx file in the repository and view in Tableau Reader.
    - Note: This is NOT a finalized Tableau presentation, it is an initial exploration of the dataset. Therefore, it is not meant to portray a final presentation and familiarity with Tableau or other visualization software may be required to follow along within the packaged workbook. Each worksheet contains notes collected from the visualizations above them.
- **Section 5:** Final Presentation
    - Follow this link to view the explanatory Tableau workbook for Part 1 of this analysis: https://public.tableau.com/views/FordGoBikeAnalysisPart1/PRE-PRESENTATIONNOTES?:display_count=y&:origin=viz_share_link

# Part 2: Time and Location Analysis

Coming soon.


# Part 3: Trends Over Time Analysis

Coming soon.
