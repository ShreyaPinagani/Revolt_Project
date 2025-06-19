# Massachusetts BEV Linear Regression Forecasting (20 Cities)

## Project Overview
This project delivers **linear regression-based forecasts** for Battery Electric Vehicle (BEV) adoption across 20 major cities in Massachusetts, providing 1-year, 3-year, and 5-year projections. All analytics, risk assessments, and infrastructure readiness studies are based strictly on **official state targets** and **verified government data**.


## Streamlit Application

**Live App:** [Streamlit BEV Forecasting Dashboard](YOUR_STREAMLIT_CLOUD_URL_HERE)  
*(Replace with your actual Streamlit Cloud link once deployed)*


## Data Sources & Authenticity

### Primary Government Data Sources

- **Massachusetts Department of Energy Resources (DOER)**
  - [MOR-EV Rebate Program](https://www.mass.gov/info-details/mor-ev-rebate-program)  
    Official statistics, EV adoption targets, and registration data  
    (13,800 rebates Jan–Sep 2024, State Target: 200,000 EVs by 2025)
  - [Massachusetts 2024 Climate Report Card – Transportation](https://www.mass.gov/info-details/2024-massachusetts-climate-report-card-transportation-decarbonization)  
    Current ZEVs: 66,025 (January 2024) | Record sales: 11,000 (Nov–Dec 2024)

- **US Census Bureau**  
  - [Population Estimates Program](https://www.census.gov/programs-surveys/popest.html)  
  - [American Community Survey (ACS) 2023 5-Year Estimates](https://www.census.gov/programs-surveys/acs/)  
    - Table S1501: Educational Attainment  
    - Table S0801: Commuting Characteristics  
    - Table DP04: Housing Characteristics

### Data Verification

- **Population:**  
  - [Massachusetts Demographics](https://www.massachusetts-demographics.com/cities_by_population)  
  - [Census Bureau QuickFacts](https://www.census.gov/quickfacts/)  
  - [UMass Donahue Institute](https://donahue.umass.edu/)

- **Income:**  
  - [DataUSA Boston, MA](https://datausa.io/profile/geo/boston-ma/)  
  - [Census Reporter](http://censusreporter.org/)

- **EV Program & Infrastructure:**  
  - [MOR-EV Statistics Dashboard](https://mor-ev.org/statistics)  
  - [Mass.gov Electric Vehicles](https://www.mass.gov/electric-vehicles)  
  - [Alternative Fuels Data Center: MA](https://afdc.energy.gov/laws/all?state=MA)  
  - [MassDOT EV Infrastructure](https://www.mass.gov/orgs/massachusetts-department-of-transportation)  
  - [Boston EV Charging](https://www.boston.gov/departments/transportation/curbside-ev-charging)  
  - [Cambridge EV Programs](https://www.cambridgema.gov/Departments/communitydevelopment/evchargingstations)


## Deliverables

- **Forecast Reports:** Linear regression projections of BEV adoption for each city (1, 3, and 5 years)
- **Priority Ranking:** City rankings using authentic demographic and economic factors (stacked bar charts)
- **Risk Matrix:** Identification of adoption barriers across all cities
- **Infrastructure Feasibility:** EV charging infrastructure and grid readiness analysis


## Authenticity Guarantee

- All forecasts, analyses, and rankings are **based solely on official government sources** (see above).
- No simulated or artificial BEV growth rates are used; projections are realistic allocations of **state-level targets**.
- Every data point is **traceable and verifiable** via the links provided above.


## Getting Started

1. **Clone the repository:**
   git clone https://github.com/ShreyaPinagani/Revolt_Project.git
   cd Revolt_Project

2. **Install dependencies:**
   pip install -r requirements.txt

3. **Run locally with Streamlit:**
   streamlit run app.py

4. **Or visit the hosted app:**
   Streamlit BEV Forecasting Dashboard
