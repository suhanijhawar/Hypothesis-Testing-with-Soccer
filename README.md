# Hypothesis-Testing-with-Soccer

## Project Overview
This project aims to statistically analyze whether more goals are scored in women's international soccer matches than men's, focusing specifically on FIFA World Cup matches since January 1, 2002. Using historical match data and hypothesis testing, the project investigates a potential difference in the average goals scored in official matches.

## Table of Contents
- Project Overview
- Dataset
- Hypothesis
- Installation
- Analysis Process
- Results
- Contributing
- License

## Dataset
The data consists of two CSV files:
- women_results.csv: Contains the results of every official women's international soccer match since the 19th century.
- men_results.csv: Contains the results of every official men's international soccer match since the 19th century.
These datasets include match details such as:
- Date
- Tournament
- Team scores
- Location
For the analysis, only FIFA World Cup matches from 2002-01-01 onward are used.

## Hypothesis
The hypothesis is based on the comparison of goals scored in men's and women's FIFA World Cup matches:
- Null Hypothesis (H₀): The mean number of goals scored in women's international soccer matches is the same as in men's matches.
- Alternative Hypothesis (H₁): The mean number of goals scored in women's international soccer matches is greater than in men's matches.
We use a significance level of 10% (α = 0.10) for the hypothesis test.

## Installation
- Clone the repository:
`git clone https://github.com/username/soccer-goals-analysis.git`
- Navigate to the project directory:
`cd soccer-goals-analysis`
- Install the required dependencies:
`pip install -r requirements.txt`

## Analysis Process
The project involves the following steps:
- Data Preprocessing: Filter the datasets to include only FIFA World Cup matches from 2002 onward.
- Exploratory Data Analysis (EDA): Visualize and summarize the goals data for both men’s and women’s matches.
- Hypothesis Testing: Conduct a statistical hypothesis test (e.g., t-test) to compare the average goals scored in men's and women's matches.
- Interpretation: Analyze the p-value and determine whether to reject or fail to reject the null hypothesis based on the significance level of 10%.

## Results
The result of the hypothesis test will indicate whether there is statistical evidence to support the claim that more goals are scored in women's FIFA World Cup matches compared to men's.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request if you'd like to contribute to the project.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
