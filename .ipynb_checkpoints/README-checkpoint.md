# datavis-challenge

## Overview
This project analyzes the effectiveness of various drug regimens on mice with squamous cell carcinoma (SCC).

## Files
- `datavis-challenege.ipynb`: The main analysis notebook.
- `Mouse_metadata.csv`: Contains metadata about the mice.
- `Study_results.csv`: Contains the results of the study.

## Instructions
1. Clone the repository.
2. Open the Jupyter Notebook and run the analysis.

## Results
1. Tumor Volume Over Time for a Single Mouse Treated with Capomulin:
When plotting the tumor volume over time for a single mouse treated with Capomulin, it was observed that the tumor volume generally decreased over time. This suggests that the Capomulin treatment may be effective in reducing tumor size in this particular case.

2. Correlation Between Mouse Weight and Tumor Volume:
The correlation coefficient between mouse weight and average tumor volume for mice treated with Capomulin was calculated to be approximately 0.84. This indicates a strong positive correlation, meaning that as the weight of the mouse increases, the tumor volume also tends to increase. 
A linear regression model was applied to this data, and the resulting regression line was plotted alongside the data points. The positive slope of the regression line further supports the correlation finding, showing that there is a tendency for larger mice to have larger tumor volumes under the Capomulin treatment.

3. Effectiveness of Capomulin:
The overall trend observed from the tumor volume vs. time plot for an individual mouse and the strong correlation between weight and tumor volume suggest that while Capomulin may reduce tumor size, its effectiveness may vary based on the weight of the mouse. This could imply that dosage or other weight-related factors need to be considered when administering the treatment.

4. General Observation:
The analysis shows that Capomulin is potentially effective, but the relationship between weight and tumor volume needs to be carefully managed to optimize treatment outcomes. Further studies with more controlled variables could help to better understand these dynamics and improve the effectiveness of the treatment.

5. Potential Outliers:
Additional analysis could be conducted to identify any outliers in the data that might represent unusual responses to the treatment, which could offer insights into factors affecting the efficacy of Capomulin.

These findings provide a good foundation for further research and potential adjustments in the treatment strategy to optimize the benefits of Capomulin.