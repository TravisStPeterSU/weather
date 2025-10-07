# Rainfall Analysis: Seattle, WA vs. Portland, ME

> A project analyzing rainfall trends between Seattle, WA and Portland, ME.

---

## Project Overview

A project analyzing rainfall trends between Seattle, Washington and Portland, Maine. Analyzing historical rainfall data from the National Oceanic and Atmospheric Administration (NOAA) the analysis explores both the frequency and quantity of rainfall to test common assumptions about which city is “rainier.”

- **Objective:** To analyze, compare, and visualize rainfall trends between Seattle, WA and Portland, ME.
- **Domain:** Climate / Environmental Sciences
- **Key Techniques:** Exploratory Data Analysis, Data Cleaning / Processing, Time Series Analysis, Data Visualization

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND
- **Description:**
  - **Features:**
    - Station: Station identification code
    - Name: Station Name
    - Date
    - DAPR: Number of days included in the multiday precipitation total (MDRP)
    - MDPR: Multiday precipitation total (inches)
    - PRCP: Precipitation (inches)
    - SNOW: Snowfall (inches)
    - SNWD: Snowfall Depth (inches)
    - WESD: Water equivalent of snow on the ground (inches)
    - WESF: Water equivalent of snowfall (inches)
  - **Size:**
  - **Format:** Comma Separated Values (.csv)
- **License:** NA

---

## Analysis

- Inspecting and cleaning both datasets
  - Handling missing or incorrect values
- Data Preparation
  - Merge and tidy the data.
- Exploratory data analysis and visualizations
- Conclusion
  - Comparison using descriptive statistics

---

## Results

- Findings
  - Seattle's average daily precipitation was 0.11 inches, while Portlands was slightly higher at 0.13 inches.
    - Seasonal trends show that Seattle's rainfall peaks in the winter months (November - January). Portland's rainfall is more evenly distributed throughout the year, with heavier single day rain in midsummer. 
    - Statistical testing showed that the average daily precipiation differed significantly in 3 months
        - January: Seattle had more rain on average than Portland.
        - July and August: Portland had more rain on average than Seattle.
    - Testing also showed that Seattle had a significantly higher proportion of rainy days in 8 months.
        - January - May, and October - December
- Conclusion
    - Based on this analysis, Seattle, Washington experiences rain more frequently, but Portland, Maine recevies more rain overall. 

---

## Authors

- Travis St Peter - [TravisStPeterSU](https://github.com/TravisStPeterSU)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Libraries
  - pandas, numpy, matplotlib, seaborn, calendar, scipy, statsmodels.