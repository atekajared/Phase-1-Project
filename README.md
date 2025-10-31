# Aviation Safety Analysis: Identifying Low-Risk Aircraft Types
# Project Overview
This project analyzes historical aviation accident data to identify the safest aircraft types for Ateqa Holdings Limited's expansion into aviation operations. The goal is to minimize operational risks while establishing a safety-first reputation in this new industry.

# Business Problem
Ateqa Holdings Limited is expanding into aviation by purchasing and operating aircraft for commercial and private enterprises. We need to identify the lowest-risk aircraft types to minimize operational risks in this new business venture.

# Objectives
Analyze historical aviation accident data to identify safety patterns

Determine which aircraft characteristics correlate with lower accident rates

Provide data-driven recommendations for aircraft acquisition

# Dataset
The analysis uses the Aviation_Data.csv dataset containing 90,348 aviation accident records with 31 features including:

Aircraft make and model

Engine type and count

Injury severity and totals

Weather conditions

Flight phase

Accident location and date

# Key Findings
Accident Trends
Aviation accidents show significant fluctuations over time with notable peaks and declines

The dataset spans from 1948 to recent years, providing comprehensive historical coverage

# Injury Severity Analysis
Fatal accidents: 85,183 (94.3%)

Non-fatal incidents: 2,219 (2.5%)

Minor injuries: 218 (0.2%)

Serious injuries: 173 (0.2%)

Unknown/Unavailable: 2,555 (2.8%)

# Aircraft Category Analysis
Airplanes: 27,617 accidents (most common)

Helicopters: 3,440 accidents

Gliders: 508 accidents

Balloons: 231 accidents

Gyrocraft: 173 accidents

# Safety Patterns
Weather Conditions: 77,303 accidents occurred in Visual Meteorological Conditions (VMC) vs 5,976 in Instrument Meteorological Conditions (IMC)

Flight Phase: Landing (15,428) and Takeoff (12,493) phases account for the highest number of accidents

Aircraft Damage: Substantial damage (64,148) is most common, followed by destroyed aircraft (18,623)

# Visualizations 


# Methodology
Data Loading & Understanding: Initial exploration of dataset structure and quality

Data Cleaning: Handling missing values, date conversion, and feature engineering

Exploratory Analysis: Trend analysis, injury categorization, and aircraft type evaluation

Safety Pattern Identification: Correlation analysis between aircraft characteristics and safety outcomes

# Recommendations
Based on the analysis, the following aircraft characteristics correlate with lower operational risk:

Aircraft Categories: Consider the relative safety records of different aircraft types

Engine Configuration: Single-engine vs multi-engine safety profiles

Operational Conditions: Weather and flight phase risk mitigation strategies

Maintenance History: Aircraft damage patterns and maintenance requirements

# Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

# Project Structure
student.ipynb: Main analysis notebook

Aviation_Data.csv: Source dataset

README.md: Project documentation

# Next Steps
Further analysis could include:

Regional safety pattern analysis

Specific manufacturer safety comparisons

Temporal safety trend analysis

Economic impact assessment of safety recommendations

