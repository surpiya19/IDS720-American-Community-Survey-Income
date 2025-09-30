# ACS Demographics and Income Data Analysis

# Estimating Labor Market Returns to Education

The primary goal is to explore the relationship between educational attainment and wages in the United States using real-world data from the American Communities Survey (ACS).

The notebook walks through a series of steps to clean, process, and analyze the dataset, culminating in an investigation of the "sheepskin effect"—the idea that a formal degree or diploma provides a significant financial return beyond the value of the knowledge acquired.

## Dataset
The analysis uses a 10% sample of the 2017 American Communities Survey (ACS), which is a survey conducted by the U.S. Census Bureau. The raw data, in a Stata (.dta) file format, is loaded directly from a URL into a pandas DataFrame. The dataset contains approximately 100 variables, representing a 0.1% sample of the total U.S. population.

### Data Loading and Initial Inspection

Exercise 1-3: The notebook begins by loading the US_ACS_2017_10pct_sample.dta file. It then asks the user to determine the total number of observations and variables in the initial dataset.

Exercise 4-7: The user is instructed to inspect the variable names and a random sample of the data to identify potential data quality issues.

### Analyzing Labor Market Returns
Exercise 10-15: The core of the analysis focuses on calculating the average total income (inctot) for different educational attainment levels. The notebook specifically compares the average income of:
- High school graduates (grade 12)
- College graduates (4 years of college)
- High school dropouts (various grade levels from n/a up to grade 11)
- Graduate degree holders (5+ years of college)

### Key Findings and Conclusion

The analysis reveals a significant jump in average income for individuals who complete their high school diploma (grade 12) and a very large increase for those who earn a college degree. In contrast, there is minimal or no income increase between individual years of high school (e.g., from grade 9 to 10 or 10 to 11).

This pattern is interpreted as evidence of the "sheepskin effect", which suggests that employers value the credential (the diploma or degree) as a signal of an individual's persistence and ability, rather than just the specific knowledge gained.
