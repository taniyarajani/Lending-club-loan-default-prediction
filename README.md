# Lending-club-loan-default-prediction
LC
Lending Club (LC) offers an online platform for matching borrowers seeking loans and lenders looking to make an investment. 
LC issues personal loans between $1000 and $40,000 for 36 to 60 month durations. Interest rates on these loans are determined based on a variety of information, including credit rating, credit history, income, etc. 
Based on this, LC assigns a grade for each loan, ranging from A for safest loans to G for highest risk; subgrades are also assigned within each grade. 
Loans are split into $25 notes, which investors can purchase. LC provides access to their data (https://www.lendingclub.com/info/downloaddata. action - sign up required). Large sets of data are provided in different files. For the purpose of this analysis, I have used a data extract on loans issues in the first 6 months of 2015. The data carries information on 36 month loans, which will all have completed their term by now. 
Some loans were fully paid back, while others were “charged off” (defaulted).


Steps involved in the analysis and prediction of loan deafult -

1. Exploratory Data Analysis
2. Missing Value Imputation
3. Build Decision Trees, Random Forest and GBM to predict default
4. Profit curve analysis to evaluate potential customers to target for maximum profit
