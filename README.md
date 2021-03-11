# BTC_corr
This project was created with the help of @realHardyStocks to gain deeper insights into the markets through statistical analysis.In this project, 
Pearson correlation coefficient is calculated between Bitcoin and the top postively & negatively coorelated equites that are in S&P 500(btc_corr).
Code for comparing different sets of equites is also provided (stock_corr).A CSV file containing all 505 S&P stocks (plus Bitcoin) data starting 1st December 2020 is provided.

Credits:  <br/> pandas.pydata.org <br/>
          interviewqs.com (for stock_corr.ipynb)
          
          
# Limitations:
https://towardsdatascience.com/the-black-swans-in-your-market-neutral-portfolios-part-i-7521683a7317
Decorrelation does not imply independence; so market-neutral portfolios aren’t always market-neutral.
A related flaw of the use of Pearson’s correlation in finance is the assumption that linearity captures the essence 
of any association between two random variables. The reality though is that all regression models are both linear and nonlinear, 
depending on what observations of input phenomena are used as reference.
          
          
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5079093/
Correlation does not imply causation.A relationship between two variables is sometimes taken as 
evidence that one causes the other. This is, however, often not true.Thus there can be no conclusion made regarding the existence or the direction of a cause-and-effect relationship only 
from the fact that two variables are correlated. Determining whether there is an actual cause-and-effect relationship requires further investigation, even when the relationship between 
the variables is statistically significant, a large effect size is observed, or a large part of the variance is explained.


https://www.researchgate.net/publication/278412602_The_Pearson_Correlation_Model_-_Work_of_the_Devil
The simplicity & linearity of peason correlation coefficient limits the model to only few meaningful financial associations since a lot of them 
are non-linear.Financial correlations often display correlation regimes. Hence different time frames can lead to very different correlation results
Only if the data set is linear, sufficient data with few outliers is present, different correlation regimes have been scrutinized, and the causality  
has  been  exogenously  analyzed  and  accepted,  can the  Pearson  model  give  sensible results.



