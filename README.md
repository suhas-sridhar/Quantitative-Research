# Quantitative-Research
An attempt was made to incorporate machine learning with traditional Quantitative Investing strategies to build a long-short portfolio that is rebalanced monthly that can potentially beat the SPY index.

I combined data from CRSP-monthly with COMPUSTAT to get a final table that had value-related variables for each stock (P/E ratio etc) as my strategy involved combining
momentum, value and machine learning to come up withe a compound strategy to attempt to beat the market. 

The CRSP monthly data was downloaded from WRDS which I had access to while I was a student. The CRSP dataset is not uploaded on github.

Unfortunately the ML model did not have any predictive power. Further research can be performed to explore features that might have better predictive power.
A sliding window of data can also be implemented to ensure that the past N-year data is considered, and not all data up to current timestamp.

LSTMs and Tranformers can be explored to see if they have better predictive power.
