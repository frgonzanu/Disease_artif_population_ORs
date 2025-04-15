# _Disease_ artificial population
This project aims to simulate an artificial population of individuals with characteristics defined based on statistics and scientific literature on risk factors associated with a specific disease. Each individual in the synthetic population is assigned a set of variables (such as age, sex, lifestyle habits, clinical markers, etc.) realistically distributed according to known epidemiological data.

Using these variables, a personalized probability of developing the disease is calculated for each individual, based on risk models derived from scientific studies. This allows for:
  - Exploring the impact of different risk factors at both individual and population levels.
  - Evaluating prevention or screening strategies based on risk profiles.
  - Generating synthetic data for training and validating predictive models in contexts where real data are scarce or sensitive.

The approach combines stochastic data generation with conditional logic and risk formulas extracted from scientific evidence, providing a controlled environment for exploratory analysis, simulations, or even educational purposes.

____________________________________________________________________

To develop this project, we first researched environmental and genetic risk factors for a specific disease and compiled the data into a structured database (see TABLE.xlsx). Using this information, we built a model based on the Odds Ratios (ORs) of each risk factor. This model was then used to calculate the probability of disease for each individual, based on personal attributes such as age, sex, genetics, smoking status, etc. Finally, we simulated whether each individual developed the disease or not.

____________________________________________________________________

Once the simulated population was generated and converted into a dataframe, further analysis could be performed to explore the disease outcome. A suggested workflow includes:

  - Building a linear model using the full dataset.
  - Identifying the most significant variables (those with highest statistical significance, e.g. ***).
  - Creating a second linear model including only these significant predictors.
  - Investigating scientific literature on relevant risk factors and associated conditions.


If you feel confident, try to 'crack' and find out the disease hidden in the population! (simulated_population.csv into the .ZIP file) Good luck! ;)
