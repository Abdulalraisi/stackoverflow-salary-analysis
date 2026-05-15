# Stack Overflow Developer Salary Analysis

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Motivation
The goal of this project is to analyze Stack Overflow Developer Survey data to understand what factors are connected to developer salary. I wanted to explore how professional coding experience, education level, and remote work type relate to yearly compensation, and whether a machine learning model can predict developer salary.

## Files in the Repository
- `stackoverflow_salary_analysis.ipynb`: Jupyter Notebook containing the full analysis, visualizations, machine learning model, evaluation, and predictive scenario.
- `stackoverflow_cleaned_salary_data.csv`: Cleaned version of the Stack Overflow survey data used for this analysis.
- `schema.csv`: Data dictionary explaining the survey columns.
- `README.md`: Project overview and summary.

## Questions Explored
1. Which numeric features are most related to salary?
2. Does education level affect developer salary?
3. Does remote work type affect developer salary?
4. Can we predict developer salary using survey data?

## Summary of Results
The analysis showed that professional coding experience has a positive relationship with yearly compensation. Developers with more professional coding experience generally reported higher salaries, although there was still a lot of variation.

Education level also appeared to have some relationship with salary. Developers with higher education levels had different median salaries, but salary is also likely affected by other factors such as country, experience, employment type, and remote work.

Remote work type also showed differences in median yearly compensation. However, this relationship may also be influenced by other factors such as location and experience.

A linear regression model was trained to predict yearly compensation. The model had an R² score of about 0.57, meaning it explained around 57% of the variation in salary. The RMSE was about $37,829, meaning the model's predictions were off by about that amount on average.

## Acknowledgments
The data used in this project comes from the Stack Overflow Developer Survey.
