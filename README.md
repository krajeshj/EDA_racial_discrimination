# Examining Racial Discrimination in the US Job Market

### Background
Racial discrimination continues to be pervasive in cultures throughout the world. Researchers examined the level of racial discrimination in the United States labor market by randomly assigning identical résumés to black-sounding or white-sounding names and observing the impact on requests for interviews from employers.

### Data
In the dataset provided, each row represents a resume. The 'race' column has two values, 'b' and 'w', indicating black-sounding and white-sounding. The column 'call' has two values, 1 and 0, indicating whether the resume received a call from employers or not.

Note that the 'b' and 'w' values in race are assigned randomly to the resumes when presented to the employer.
### Exercises
You will perform a statistical analysis to establish whether race has a significant impact on the rate of callbacks for resumes.
Answer the following questions in this notebook below and submit to your Github account.
* What test is appropriate for this problem? Does CLT apply?
* What are the null and alternate hypotheses?
* Compute margin of error, confidence interval, and p-value. Try using both the bootstrapping and the frequentist statistical approaches.
* Write a story describing the statistical significance in the context or the original problem.
* Does your analysis mean that race/name is the most important factor in callback success? Why or why not? If not, how would you amend your analysis?
You can include written notes in notebook cells using Markdown:
In the control panel at the top, choose Cell > Cell Type > Markdown



### Files

File|Description
---------|-------------------------------------------------------------------------------------------------------------------
[code/sliderule_dsi_inferntial_statistics_exercise_2.ipynb](https://github.com/krajeshj/EDA_racial_discrimination/blob/master/code/sliderule_dsi_inferential_statistics_exercise_2.ipynb)|  Jupyter Notebook containing code
[data/us_job_market_discrimination.dta](https://github.com/krajeshj/EDA_racial_discrimination/tree/master/data)| data for the notebook
 
### Directories

Directory|Description
---------|---------------------------------------------------------------------------------------------------
code | Contains Jupyter notebook 
data| contains data
 
### Reference
1. Markdown syntax: http://nestacms.com/docs/creating-content/markdown-cheat-sheet
2. Experiment information and data source: http://www.povertyactionlab.org/evaluation/discrimination-job-market-united-states
3. Scipy statistical methods: http://docs.scipy.org/doc/scipy/reference/stats.html
4. Markdown syntax: http://nestacms.com/docs/creating-content/markdown-cheat-sheet
5. Formulas for the Bernoulli distribution: https://en.wikipedia.org/wiki/Bernoulli_distribution
