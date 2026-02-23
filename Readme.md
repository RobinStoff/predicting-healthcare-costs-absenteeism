<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/a2aeb9c5-fe7c-486e-883d-4c6498915dbb" />


# Working Hours and Health-Related Absenteeism in the EU (2019)

End-to-end data analytics project exploring the relationship between average weekly working hours and health-related absenteeism across EU countries.

---

## Research Question

Is there a relationship between average weekly working hours and absenteeism due to health problems across EU countries in 2019?

---

## Key Findings

- A strong negative correlation was found between weekly working hours and absenteeism (r = -0.661).
- Linear regression confirmed a statistically significant relationship.
- Countries with longer working hours tend to report lower absenteeism.
- However, this association is not causal and likely reflects structural and institutional differences.

---

## Methodology

1. Data acquisition (Eurostat)
2. Data cleaning (handling missing values and Eurostat flags)
3. Feature extraction (country-level 2019 data)
4. Data integration (merging datasets)
5. Correlation analysis
6. Linear regression
7. Outlier analysis
8. Interpretation & limitations

---

## Tools Used

- Python
- pandas
- numpy
- matplotlib
- scipy / statsmodels
- Jupyter Notebook

---

## Project Structure
├── notebook.ipynb
├── README.md
├── requirements.txt
└── .gitignore


---

## Limitations

- Country-level aggregated data (risk of ecological fallacy)
- No control variables included (e.g., GDP, labor structure)
- Results represent association, not causation

---

## Future Improvements

- Add control variables (GDP per capita, healthcare spending)
- Multi-variable regression analysis
- Panel data across multiple years
- Individual-level analysis


