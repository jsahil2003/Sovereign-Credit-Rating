# Towards Fairness and Accuracy: A Comparative Study of Sovereign Credit Ratings by Global Agencies

## Abstract

This project examines the factors which influence sovereign credit ratings assigned by three prominent global credit rating agencies: Moody's, Fitch, and Standard & Poor (S&P). We delve into the determinants of these ratings and their implications for countries, with a particular focus on the countries in the global south.

Our findings reveal a concerning negative bias toward countries categorised under the global south, indicating potential disparities in the rating assessment process. Additionally, we find that macroeconomic indicators such as Foreign Direct Investment (FDI) and external debt fail to demonstrate statistical significance in explaining variations in sovereign ratings. Furthermore, socio-political factors including the Human Development Index and government efficiency score exhibit similar insignificance in our analysis.

This project report investigates the transition probabilities of sovereign credit ratings using a Transition Probability Matrix (TPM) framework.The study utilises historical sovereign credit rating data to construct a TPM, which quantifies the likelihood of transitions between different credit rating categories over specific time periods.It examines the concept of sticky ratings, wherein certain ratings exhibit persistence or resistance to change over time, influencing the overall dynamics of the credit rating landscape.

Through empirical analysis and statistical modelling, this research sheds light on the factors driving sovereign credit rating transitions and the persistence of sticky ratings. Such insights offer valuable implications for investors, policymakers, and financial institutions in managing credit risk exposure, designing investment strategies, and formulating sovereign debt policies.

## Repository Structure

- **`regression.R`**: Contains the regression analysis code used to explore the factors influencing sovereign credit ratings.
- **`markov-chain.R`**: Implements the Markov chain analysis to study the dynamics of sovereign credit rating transitions.
- **`transition-matrix.R`**: Includes the code for constructing the Transition Probability Matrix (TPM), which quantifies the likelihood of ratings transitions.
- **`scr_regression.ipynb`**:  Contains the regression analysis code used to explore the factors influencing sovereign credit ratings using python and trying different transformations on variables.
- **`tpm.ipynb`**: Includes the code for constructing the Transition Probability Matrix (TPM) using Python, which quantifies the likelihood of ratings transitions.

## Data Files

- **`/data_sca/global_south.xlsx`**: Contains the list of countries classified as part of the global south. This data is used to analyze potential biases in sovereign credit ratings.
- **`/data_sca/g20.xlsx`**: Lists the countries that are members of the G20, also used in the bias analysis within the regression models.
- **`/data_sca/credit-rating-transitions.xlsx`**: Provides historical credit rating data for various countries, used in constructing the Transition Probability Matrix (TPM).
- **`/data_sca/transition-matrix-moodys.xlsx`**: Contains the calculated transition matrix specific to Moody's sovereign credit ratings.
- **`/data_sca/data.xlsx`**: The master dataset that includes all factors used in the regression analysis, such as macroeconomic indicators and socio-political factors.
