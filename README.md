# Global COVID-19 Vaccination and Health Outcome Analysis

This repository presents a comprehensive exploratory data analysis of global COVID-19 trends, with a focus on vaccination disparities and their relationship to health outcomes across the six World Health Organization (WHO) regions. The project investigates how differences in vaccine access, healthcare infrastructure, and regional policy responses influenced the spread and severity of the pandemic.

## Project Objectives

- Evaluate global disparities in COVID-19 vaccination coverage.
- Examine the relationship between vaccination rates and case fatality rates (CFR).
- Analyze cumulative case and death trends over time by country and region.
- Provide visual and statistical insights to support future global health preparedness and equity.

## Key Visualizations

### Vaccination Coverage by WHO Region

This boxplot illustrates vaccination rates per 100 individuals across WHO regions. The African Region (AFR) exhibits the lowest coverage, while the Western Pacific (WPR) and European Region (EUR) show the highest median rates.

<img width="828" alt="Screenshot 2025-05-08 at 11 23 26 AM" src="https://github.com/user-attachments/assets/aa1fda86-f25e-453f-865a-7d0c82844cb6" />

---

### Vaccination Rates and Case Fatality Rates

This scatterplot shows the inverse relationship between vaccination rates and case fatality rates across countries. Regions with higher vaccine coverage generally have lower fatality rates, indicating the public health impact of vaccination campaigns.
<img width="794" alt="Screenshot 2025-05-08 at 11 23 54 AM" src="https://github.com/user-attachments/assets/2ffd099b-d6f2-4450-b0d2-4be4af508cf0" />


---

### Cumulative COVID-19 Deaths by Country

This bar chart presents total reported COVID-19 deaths among the ten most affected countries. The United States has the highest reported fatalities, followed by Brazil and India.

<img width="871" alt="Screenshot 2025-05-08 at 11 25 07 AM" src="https://github.com/user-attachments/assets/7c4556da-3d79-437c-9ea7-0a0846ca4268" />

---

## Repository Structure
/notebooks
final_report_code.ipynb # Jupyter Notebook with code for data processing and visualization
/reports
final_report.pdf # Full written report summarizing findings and implications
/images
boxplot_vaccination.png
scatter_vaccination_cfr.png
bar_total_deaths.png



## Technologies and Libraries Used

- Python 3
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- numpy

## Included Files

- `Covid19-vacinie-analysis.ipynb` – Contains all data cleaning, transformation, and visual analysis.
- `final_report.pdf` – A formal report detailing the analytical approach, findings, limitations, and recommendations.

## Data Source

World Health Organization (WHO) COVID-19 Dashboard  
https://data.who.int/dashboards/covid19/data

## License

This repository is distributed under the MIT License. Use and modification are permitted with appropriate attribution.

