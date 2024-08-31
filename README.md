# Quant-Research-Forage
[JPMorgan Chase &amp; Co. Job Simulation](https://www.theforage.com/simulations/jpmorgan/quantitative-research-11oc)

## Task 1
Given past monthly data on Natural Gas (Natural Gas.csv), predict the price on a certain date in the past (interpolation) as well as one year in the future (extrapolation).
  - Performed 2 methods, a linear regression and a sine curve fitting. Plotted the graphs of both methods and compared them to find the better method which I employed in a prediction function.

## Task 2
Create a prototype pricing model to estimate the value of a deal based on many factors (the price at which the gas was bought, the price at which the price was sold, storage costs etc.)
  - Created a Python function that takes these into account.
    
## Task 3
Given data on loan borrowers (Task 3 and 4_Loan_Data.csv), with various metrics (their income, total loans outstanding etc.) and whether they have defaulted, train a model that predicts the probability of default for a certain borrower.
  - Performed a Logistic Regression on multiple variables to get a probability of default of a borrower.

## Task 4
Given data on loan borrowers (Task 3 and 4_Loan_Data.csv), categorise the FICO scores (a measure of credit score) into different categories (bucketing) in a process called quantisation with either Mean Squared Error or Log-Likelihood.
- Performed 2 methods, a brute-force method and a more efficient dynamic programming method.
