# Predict US Election Result
This repository contains code and data for our final project in Data 102 at UC Berkeley.

In this project, we analyzed datasets on candidates in the 2018 US House and Senate primaries to explore two key questions:

Can we predict the election results of the Democratic candidates via their identities and endorsements?
Does the amount of disbursement candidates spend affect their results in elections?
To answer the first question, we built prediction models using frequentist and Bayesian logistic regression and random forests. We found that a candidate's race, party support, and certain endorsements were significant predictors of their election result.

For the second question, we used causal inference techniques including propensity score matching to estimate the causal effect of candidate disbursement amounts on their election results. We found evidence for a causal relationship, especially for Democratic candidates.

## Authors

- Zizhuo (Tina) Chen
- Ziyi Ding 
- Laura Li
- Nei Fang

## Contents

The repository contains the following:

### Data

- `dem_candidate.csv`: Dataset containing information on Democratic candidates in 2018 House and Senate primaries. From [FiveThirtyEight](https://github.com/fivethirtyeight/data/tree/master/primary-candidates-2018).

- `rep_candidate.csv`: Dataset containing information on Republican candidates in 2018 House and Senate primaries. From [FiveThirtyEight](https://github.com/fivethirtyeight/data/tree/master/primary-candidates-2018). 

- `candidate_summary_2018.csv`: Dataset containing spending data for candidates in 2018 elections. From [Federal Election Commission](https://www.fec.gov/data/browse-data/?tab=bulk-data).

### Notebooks

- `data.ipynb`: Notebook for cleaning and merging the datasets.

- `Final_Project_Code.ipynb`: Sum notebook for prediction analysis using GLMs, random forest, and causal inference analysis using propensity score matching. 

### Report

- `data_102_final_project.pdf`: Final project report detailing problem statement, data, methods, results, and discussion.

## Usage

The notebooks require Python 3 and use standard data science libraries including pandas, matplotlib, seaborn, sklearn, and pymc3.

To run the notebooks:

1. Clone this repository 
2. Install dependencies (`pip install -r requirements.txt`)
3. Run Jupyter notebook from the repo directory 
4. Open and run the notebooks

## License

This repository is licensed under the MIT License. Feel free to use and distribute the code/report as long as you cite this repository.
