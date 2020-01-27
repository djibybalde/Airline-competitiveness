# Airline-competitiveness: Evidence from the U.S. Domestic Market

# <center> ![AilinePhoto](https://images.theconversation.com/files/65252/original/image-20141123-1052-1y8mjrc.jpg?ixlib=rb-1.1.0&q=45&auto=format&w=926&fit=clip)
  
# Contents
## DataProcessing
  1. 
  2. …
  

## PanelDataModeling
  0. Import Libraries and Load Data
  1. Data Preparation for PanelData Model

### I. Bassic Panel Model
  1. PooledOLS model
  2. RandomEffects model
  3. BetweenOLS model

### II. Testing correlated effects
  1. Testing for Fixed Effects
  2. Testing for Time Effects
  3. First Differences

### III. Comparison
  1. Comparing between modelBetween, modelRE and modelPooled models
  2. Comparing between Robust, Entity and Entity-Time mothods

### IV. Instruments as lags of order 1 and 2 of first differences
  * Campute the lags of order 1 and 2 of first differences

### V. Linear Instrumental-Variables Regression
  1. 2SLS as OLS
  2. IV 2SLS
    1. Sargan test: Testing the absence of correlation between Z and U
    2. Testing the correlation of Z and X_endog
    3. Endogeneity testing using `Durbin` and `Wu-Hausman` test of exogeneity
    4. Augmented test for testing the exogeneity of log_fare
    5. Instrumenting using two-stage least squares
    6. Homoskedasticity – Heteroskedasticity
      1. Breusch–Pagan test
      2. White test
    7. Testing Autocorrelation

### VI. GMM Estimation
  1. Exogeneity test using `Sargan-Hansen` test
  2. Exogeneity test using the augmented regression approach
  
### VII. Feasible Generalized Least Squares (GLS) and GLSA model
  
  
  
