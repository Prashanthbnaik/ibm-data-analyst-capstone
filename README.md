# IBM Data Analyst Capstone Project: Global Tech Job Market Analysis

This repository contains the final capstone project for the IBM Data Analyst Professional Certificate. It demonstrates a complete data analytics workflow—from data acquisition and cleaning to exploratory analysis, visualization, and business reporting—based on a global dataset of tech job postings.

## Project Objective

To analyze a dataset of global tech job postings with the goal of identifying regional hiring trends, demand for remote work, role types, and employment structures, enabling data-driven recommendations for both job seekers and hiring managers.

## Business Context

In the post-pandemic digital economy, demand for skilled technology professionals is rapidly evolving. Organizations increasingly adopt hybrid and remote work models, while job seekers navigate a dynamic hiring landscape. Understanding job market trends across cities, employment types, and work settings is critical for informed workforce planning.

## Tools and Technologies

- Programming: Python  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn  
- Platform: Jupyter Notebook  
- Reporting: PowerPoint  
- Dataset: Provided via IBM Skills Network (CSV format)

## Dataset Overview

The dataset contains tech job listings with attributes including:

- Job Title  
- Location  
- Company  
- Work Setting (Remote, On-site, Hybrid)  
- Employment Type (Full-time, Part-time, Contract)  
- Experience Level  
- Date Posted

## Methodology

1. Data Import and Inspection  
   - Loaded and explored dataset structure, data types, and missing values.

2. Data Cleaning and Transformation  
   - Standardized column names, handled null entries, removed duplicates, and formatted categorical fields.

3. Exploratory Data Analysis (EDA)  
   - Analyzed job distribution by city, role type, experience level, and employment setting.  
   - Used group-by aggregations to uncover patterns in hiring and work formats.

4. Data Visualization  
   - Developed clear and interpretable visualizations using Seaborn and Matplotlib.  
   - Visuals include bar plots, frequency charts, and comparative analyses.

5. Business Reporting  
   - Key findings presented in a PowerPoint slide deck, formatted for non-technical stakeholders.

## Key Findings

- Top Hiring Cities: Washington D.C., New York, and Los Angeles consistently showed the highest volume of tech job listings.  
- Remote Work Trends: A significant share of job roles are either fully remote or offer hybrid options.  
- Job Roles in Demand: High frequency observed for developer, analyst, and engineer roles.  
- Employment Structure: Full-time positions dominated the listings, followed by contract-based roles.

## Deliverables

- `Capstone_Project_Notebook.ipynb`: Fully documented Python notebook with step-by-step analysis.  
- `Final_Presentation.pptx`: Executive-level summary report for business presentation.  
- `jobs_data.csv`: Original dataset used for analysis.

## Repository Structure

```
ibm-data-analyst-capstone/
├── Capstone_Project_Notebook.ipynb     # Jupyter notebook containing full analysis
├── Final_Presentation.pptx             # Presentation of key insights and recommendations
├── jobs_data.csv                       # Input dataset (CSV format)
└── README.md                           # Project documentation
```

## How to Reproduce

1. Clone the repository:
   ```
   git clone https://github.com/Prashanthbnaik/ibm-data-analyst-capstone.git
   cd ibm-data-analyst-capstone
   ```

2. Open the notebook:
   - Use Jupyter Notebook or JupyterLab  
   - Run all cells sequentially for reproducibility

## Author

This project was completed as part of the IBM Data Analyst Professional Certificate.  
Prepared and submitted by: **Prashanth B**
