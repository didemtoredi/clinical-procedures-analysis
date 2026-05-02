# Clinical Procedure Performance Analysis

## Overview
This project analyzes clinical data to determine whether using the dominant or non-dominant hand improves performance in ultrasound-guided needle procedures.

## Research Question
Does holding the needle in the dominant hand result in faster procedure times compared to the non-dominant hand?

## Dataset
- 20 participants
- 400 total observations
- Each participant performed 10 trials per hand configuration

### Key Variables
- `hand`: Dominant (DHP) vs Non-Dominant (DHN)
- `time`: Time (seconds) to complete procedure
- `attempt`: Trial number
- Participant demographics (age, gender, background)

## Methods
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Visualization (histograms, boxplots)
- Paired t-test on participant-level averages

## Results
- Mean difference: **27.37 seconds**
- t-statistic: **3.83**
- p-value: **0.0011**
- 95% CI: **[12.40, 42.34]**

✅ Participants were significantly faster using their **non-dominant hand**

## Key Insights
- Non-dominant hand configuration led to faster and more consistent performance
- Dominant hand showed higher variability and more outliers
- Results suggest potential training implications for clinical practice

## Files
- `Ultrasound_Guided_Procedure_Report.pdf` → Full report
- (Optional) `analysis.ipynb` → Code and analysis (if added later)

## Tools Used
- Python (Pandas, Matplotlib)
- Statistical Testing (Paired t-test)

## Future Improvements
- Add regression modeling
- Control for learning effects across attempts
- Expand dataset with experienced practitioners

## Visualizations

![Histogram](visuals/histogram.png)
![Boxplot](visuals/boxplot.png)
