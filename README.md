# Exploring the 2018 General Social Survey

## Overview
This repository contains a Jupyter Notebook (`gssdashboard.ipynb`) and dashboard visualizations built from the **2018 General Social Survey (GSS)**.  
The dashboard highlights **sex differences in income, job prestige, socioeconomic index, and education**, as well as attitudes toward gender roles.  

The GSS is a nationally representative survey conducted by the National Opinion Research Center (NORC) at the University of Chicago. For 2018, 2,348 interviews were collected using full probability sampling, and demographic/profession-related data were included.

---

## Features
- **Summary Statistics by Sex**  
  - Average job prestige  
  - Average income  
  - Average socioeconomic index  
  - Average years of education  

- **Survey Responses**  
  - Attitudes toward gender roles (e.g., division of labor at home)  
  - Distribution of responses across demographic groups  

- **Visualizations**  
  - Clean tables and plots summarizing differences between men and women  
  - Comparison of socioeconomic measures and education levels  

---

## Repository Contents
- **`gssdashboard.ipynb`** – Jupyter Notebook containing code for data cleaning, analysis, and dashboard rendering.  
- **Dashboard screenshots** (`Capture.JPG`, `Capture2.JPG`) – Example views of the deployed dashboard.  

---

## Requirements
To run the notebook, you will need:  
- Python 3.8+  
- Jupyter Notebook or JupyterLab  
- Common Python libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn plotly
  ```

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/kim-minah/GSS-Dashboard.git
   cd GSS-Dashboard
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook gssdashboard.ipynb
   ```
3. Run all cells to generate the tables and dashboard visualizations.  

---

## Example Output
### Mean Income, Job Prestige, Socioeconomic Index, and Education by Sex
| Sex    | Avg Job Prestige | Avg Income | Avg Socioeconomic Index | Avg Education |
|--------|------------------|------------|-------------------------|---------------|
| Female | 44.67            | 47,191.02  | 46.58                   | 13.76         |
| Male   | 44.70            | 53,314.63  | 47.38                   | 13.69         |

*(See `Capture.JPG` and `Capture2.JPG` for full dashboard screenshots.)*  

---

## Data Source
- **2018 General Social Survey (GSS)** – [NORC at the University of Chicago](https://gss.norc.org/)  
- **2020 Census Bureau data** – for wage gap context  

---

