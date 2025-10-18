# NHANES 2021–2023 Inferential Analytics

This analysis applies inferential statistical methods-including chi-square tests, t-tests, ANOVA, and correlation—to NHANES 2021–2023 data. 
Key variables include marital status, education level, sedentary behavior, blood pressure, age, and weight. 
The project focuses on identifying associations and differences across demographic and health indicators using Python in Google Colab.

## Database Overview

**The NHANES dataset includes variables related to**:
- Marital status
- Education level
- Age
- Blood pressure
- Vitamin D levels
- Hepatitis B antibodies
- Kidney health
- Sedentary behavior
- Self-reported weight

## Questions Explored:

1. **Association between marital status and education level**  
   *Chi-square test to determine if there's a relationship between being married and having a bachelor's degree or higher.*

2. **Difference in sedentary behavior by marital status**  
   *T-test to compare mean sedentary time between married and non-married individuals.*

3. **Effect of age and marital status on systolic blood pressure**  
   *Two-way ANOVA to assess how age and marital status influence systolic blood pressure.*

4. **Correlation between self-reported weight and sedentary behavior**  
   *Pearson correlation to examine the relationship between weight and sedentary time.*

5. **Creative Analysis**  
   *A custom question developed using NHANES variables and tested using an appropriate statistical method.*

## Methods:

- Data cleaning and transformation
- Recoding categorical variables
- Handling missing and placeholder values
- Statistical testing using `scipy`, `statsmodels`, and `pandas`
- Visualizations using `matplotlib` and `seaborn`

## Files:

- `nhanes_analysis.ipynb`: Main Google Colab notebook with all code, analysis, and visualizations
- `README.md`: Project overview and instructions

## Notes:

- All placeholder values (e.g., 7777, 9999) were removed or handled appropriately.
- Frequency counts and descriptive statistics were used to validate data consistency.
- Any errors encountered during analysis are documented in the notebook with screenshots and explanations.

## How to use:

1. Open the notebook in Google Colab.
2. Run each cell sequentially to reproduce the analysis.
3. Review the summary findings at the end of each section.

---


