# Aviation Safety Analysis

## Project Overview
This project focuses on analyzing aviation accident data from the National Transportation Safety Board (NTSB) spanning the years 1962–2023. The primary goal is to identify low-risk aircraft models and provide operational safety recommendations to support a company's entry into the aviation sector.

## Objectives
- Identify low-risk aircraft models for both US and international operations.
- Analyze operational risks related to flight phases and weather conditions.
- Provide strategic safety recommendations for global aviation operations.

## Key Features
- **Data Cleaning and Preprocessing**:
  - Imputation of missing values for categorical and numerical fields.
  - Removal of irrelevant columns (e.g., `Latitude`, `Longitude`, `Schedule`).
  - Segmentation of the dataset into US and international flights.

- **Injury Severity Reclassification**:
  - **Severe Injuries**: Combined fatal and serious injuries.
  - **Non-Severe Injuries**: Combined minor injuries and uninjured outcomes.

- **Proportional Analysis**:
  - Safety performance evaluated based on the proportion of severe and non-severe injuries for aircraft models, flight phases, and weather conditions.

## Key Visualizations
1. **Aircraft Model Safety Analysis**:
   - Bar charts and scatter plots showing proportions of severe and non-severe injuries for top US and international aircraft models.

2. **Flight Phase Risk Analysis**:
   - Identification of high-risk flight phases based on the proportion of severe injuries for both US and international flights.

3. **Weather Condition Impact**:
   - Proportions of severe injuries analyzed under Visual Meteorological Conditions (VMC) and Instrument Meteorological Conditions (IMC).

4. **Trends Over Time**:
   - Line charts depicting changes in severe injury proportions for top aircraft models across years.

## Recommendations
### For US Flights:
1. Prioritize **Cessna 172M** and **172** for their strong safety performance across weather conditions and flight phases.
2. Exercise caution with **PA-28-140** and **Cessna 150** in IMC due to higher severity proportions.
3. Invest in IMC-specific training and advanced avionics to improve safety in poor weather conditions.

### For International Flights:
1. Utilize **Boeing 737** for VMC operations and **Boeing 777** for IMC conditions.
2. Develop global safety initiatives to monitor and refine operational strategies to address weather-related risks.

## Tools and Technologies
- **Python**: For data cleaning, analysis, and visualization.
- **Pandas**: Data manipulation and preprocessing.
- **Matplotlib**: Creation of detailed and customized visualizations.
- **Jupyter Notebook**: For an interactive analysis environment.

## Repository Structure
```
├── data/                   # Raw and processed datasets
├── notebooks/              # Jupyter Notebooks for analysis
├── visuals/                # Generated plots and visualizations
├── README.md               # Project overview and documentation
└── Phase_1_Project.ipynb   # Main analysis notebook
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/jakeg2320/Phase_1_Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Phase_1_Project
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Phase_1_Project.ipynb
   ```
4. Follow the notebook to explore the analysis and visualizations.

## Next Steps
1. **Expand Dataset Scope**:
   - Incorporate newer aircraft models and maintenance records for more comprehensive analysis.
2. **Pilot Error Trends**:
   - Investigate pilot error trends to develop additional safety recommendations.
3. **Interactive Dashboards**:
   - Create dashboards for real-time safety monitoring and reporting.

## Author
- **Name**: Jake G
- **Contact**: [LinkedIn Profile](https://www.linkedin.com/in/jakeg) | [Email](mailto:jakeg@example.com)

---

**Empowering data-driven decisions for safer aviation operations.**
