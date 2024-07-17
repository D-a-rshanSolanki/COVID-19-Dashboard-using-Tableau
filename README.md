# COVID-19 India Data Analysis

This repository contains datasets related to COVID-19 cases, vaccination, and testing details in India. The datasets can be used for analysis, visualization, and understanding the spread and control measures of COVID-19 in different states of India.

## Datasets

### 1. COVID-19 Cases in India
- **Filename**: `covid_19_india.csv`
- **Description**: This dataset contains the daily count of COVID-19 cases in India, including details such as the date, state, confirmed cases, cured cases, deaths, etc.
- **Columns**:
  - `Date`: Date of record
  - `State/UnionTerritory`: Name of the state or union territory
  - `ConfirmedIndianNational`: Number of confirmed cases (Indian nationals)
  - `ConfirmedForeignNational`: Number of confirmed cases (foreign nationals)
  - `Cured`: Number of cured/discharged cases
  - `Deaths`: Number of deaths
  - `Confirmed`: Total number of confirmed cases

### 2. COVID-19 Vaccination Data Statewise
- **Filename**: `covid_vaccine_statewise.csv`
- **Description**: This dataset contains the statewise vaccination data in India, detailing the number of vaccines administered across different states.
- **Columns**:
  - `State`: Name of the state or union territory
  - `Updated On`: Date of the record
  - `Total Doses Administered`: Total number of vaccine doses administered
  - `Total Sessions Conducted`: Total number of vaccination sessions conducted
  - `Total Sites`: Total number of vaccination sites
  - `First Dose Administered`: Number of first doses administered
  - `Second Dose Administered`: Number of second doses administered
  - `Male(Individuals Vaccinated)`: Number of males vaccinated
  - `Female(Individuals Vaccinated)`: Number of females vaccinated
  - `Transgender(Individuals Vaccinated)`: Number of transgender individuals vaccinated
  - `Total Covaxin Administered`: Total number of Covaxin doses administered
  - `Total CoviShield Administered`: Total number of CoviShield doses administered
  - `Total Sputnik V Administered`: Total number of Sputnik V doses administered
  - `AEFI`: Number of Adverse Events Following Immunization

### 3. Statewise Testing Details
- **Filename**: `StatewiseTestingDetails.csv`
- **Description**: This dataset contains the statewise COVID-19 testing details in India, providing information on the number of tests conducted over time.
- **Columns**:
  - `Date`: Date of record
  - `State`: Name of the state or union territory
  - `TotalSamples`: Total number of samples tested
  - `Negative`: Number of negative test results
  - `Positive`: Number of positive test results

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/covid19-india-data.git
   cd covid19-india-data

2. **Load the datasets**:
Use your preferred data analysis tools (such as Python with pandas, R, Excel, etc.) to load and analyze the data.

Example using Python with pandas:
import pandas as pd

## Load COVID-19 cases data
covid_cases = pd.read_csv('covid_19_india.csv')

## Load vaccination data
vaccination_data = pd.read_csv('covid_vaccine_statewise.csv')

## Load testing data
testing_data = pd.read_csv('StatewiseTestingDetails.csv')

3. **Analyze and visualize**:
Perform your data analysis and create visualizations to gain insights from the datasets.

## License
This repository is licensed under the MIT License. See the LICENSE file for more details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## Acknowledgments
Data sources: The datasets are sourced from official government releases and other trusted sources.
