# Using-Artificial-Intelligence-to-Predict-Property-Prices-in-NSW
The data utilised for this project is sourced from the publicly available NSW Valuer General’s office ("Bulk Property Sales Information", 2021), which details bulk NSW Property Sales Information from 1990 to present day. We will be focusing on data from 2001 to 2014. The relevant attributes contained in these datasets will be used, consisting of:
1. District Code
2. Property ID
3. Sale Counter
4. Property Unit/House Number
5. Street Name (string and numerical ID)
6. Locality (string and numerical ID)
7. Postcode
8. Area
9. Area Type
10. Contract date
11. Purchase Price
12. Zoning (string and numerical ID)
13. Primary Purpose (string and numerical ID)
14. Component Code (string and numerical ID)
15. Sale Code

The models trained on this data include:
- Random Forest Regressor 
- ADABoost Regressor, 
- Support Vector Regressor
- Decision Tree Regressor
- Neural Network
- Gradient Boosted Regressor. 

The best solution was identified through evaluating each algorithm's result with respect to absolute mean error, mean error range and R-squared percentage.

The best performing model was the Random Forest with an Absolute Mean Error of 239355.05 an Absolute Mean Error Range 505675.57 - 984385.68 and an R-Squared Percentage of 61%.
