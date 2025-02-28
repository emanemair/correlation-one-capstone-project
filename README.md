# Brain Health Analysis: Impact of Vascular Risk Factors

This repository contains the code and analysis for a project investigating the impact of vascular risk factors (hypertension, diabetes) and demographic factors (age, gender) on brain health, specifically focusing on cognitive performance and small vessel disease (SVD). This project was completed as part of the Correlation One Tech training program, under the guidance of Tarek Atwan and Enas.

## Project Overview

Brain health is crucial for overall well-being. As individuals age, various changes can lead to cognitive decline and neurodegenerative conditions. This project aims to analyze how vascular risk factors, alongside demographic factors, affect brain health, cognitive performance, and the severity of SVD.

## Data Source

[**https://www.kaggle.com/datasets/snmahsa/comprehensive-health-and-brain-imaging-dataset**]


## Methodology

1.  **Data Curation:**
    * Removed null values.
    * Identified and handled outliers using the Interquartile Range (IQR) method.
    * Clipped extreme values to the upper and lower bounds defined by the IQR to minimize their impact.
2.  **Exploratory Data Analysis (EDA):**
    * Utilized Python (with libraries like Pandas, NumPy, Matplotlib, and Seaborn) for data analysis and visualization.
    * Created scatter plots to visualize relationships between age, processing speed, SVD, diabetes, and Fazekas categories.
    * Generated boxplots to compare SVD Amended Scores between individuals with and without hypertension and diabetes.
3.  **Analysis and Interpretation:**
    * Analyzed the impact of aging, hypertension, diabetes, and other factors on brain health and SVD.
    * Drew conclusions based on the visualizations and statistical observations.

## Key Findings

* Aging is associated with structural and functional brain changes, including increased Fazekas degree and decreased processing speed.
* Hypertension and diabetes are linked to higher SVD Amended Scores, indicating increased SVD severity.
* These findings highlight the complex interplay of factors affecting brain health in aging populations.



## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn

## How to Run the Code

1.  Clone this repository.
2.  Ensure you have Python and the required libraries installed.
3.  Open and run `brain_health_analysis.ipynb` using Jupyter Notebook or JupyterLab.

## Author

* Eman Emair 
