[Los Angeles crimes Analysis Notebook](https://nbviewer.org/github/youssef-gis/Los-Angeles-crimes-Analysis/blob/main/LA_crimes_analysis.ipynb)

# Los-Angeles-crimes-Analysis
Los Angeles; often glamorized as the City of Angels; is a sprawling metropolis known for its beaches, entertainment industry, and cultural diversity. But beneath the surface lies a complex web of urban challenges, one of which is crime.
This project aims to analyze crime data from Los Angeles to identify patterns in criminal behavior. The insights derived from this analysis will help the Los Angeles Police Department (LAPD) allocate resources more effectively to address various crimes in different areas. The project leverages Python for data manipulation and visualization.

## Dataset

The dataset used in this project is a modified version of the publicly available data from [Los Angeles Open Data](https://data.lacity.org/). It includes the following columns:

- **DR_NO:** Official file number (combination of year, area ID, and additional digits).
- **Date Rptd:** Date the crime was reported (MM/DD/YYYY).
- **DATE OCC:** Date the crime occurred (MM/DD/YYYY).
- **TIME OCC:** Time the crime occurred (24-hour military time).
- **AREA NAME:** Geographic area or patrol division responsible for the area.
- **Crm Cd Desc:** Description of the crime committed.
- **Vict Age:** Age of the victim.
- **Vict Sex:** Sex of the victim (F: Female, M: Male, X: Unknown).
- **Vict Descent:** Descent of the victim (various codes for different ethnicities).
- **Weapon Desc:** Description of the weapon used (if applicable).
- **Status Desc:** Status of the crime.
- **LOCATION:** Street address where the crime occurred.

## Analysis

The analysis in this project focuses on the following aspects:

1. **Crime Frequency by Hour of Day:** Identifying the hours when crimes are most frequently committed.
2. **Night Crimes by Location:** Analyzing crimes committed during nighttime and identifying the areas with the highest frequency of night crimes.
3. **Victim Age Distribution:** Categorizing crime victims into age bins and visualizing the distribution across different age groups.

## Results

- **Peak Crime Hour:** The most frequent hour for crimes is 12:00.
- **Peak Night Crime Location:** The Central area has the highest number of night crimes.
- **Victim Age Distribution:** Individuals aged 26-45 are the most frequent victims of crime.


## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries: pandas, numpy, matplotlib, folium, geopandas

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
