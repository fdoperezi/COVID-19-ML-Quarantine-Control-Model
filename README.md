# COVID-Quarantine-control-model-Julia

Since the first recording of what we now call Covid-19 infection in Wuhan, Hubei province, China on Dec 31, 2019, the disease has spread worldwide and met with a wide variety of social distancing and quarantine policies. The effectiveness of these responses is notoriously difficult to quantify as individuals travel, violate policies deliberately or inadvertently, and infect others without themselves being detected. Moreover, the publicly available data on infection rates are themselves unreliable due to limited testing and even possibly under-reporting. In this paper, we attempt to interpret and extrapolate from publicly available data using a mixed first-principles epidemiological equations and data-driven neural network model. Leveraging our neural network augmented model, we focus our analysis on four locales: Wuhan, Italy, South Korea and the United States of America, and compare the role played by the quarantine and isolation measures in each of these countries in controlling the effective reproduction number $R_{t}$ of the virus. Our results unequivocally indicate that the countries in which rapid government interventions and strict public health measures for quarantine and isolation were implemented were successful in halting the spread of infection and prevent it from exploding exponentially. In the case of Wuhan especially, where the available data were earliest available, we have been able to test the predicting ability of our model by training it from data in the January 24 till March 3 window, and then matching the predictions up to April 1. Even for Italy and South Korea, we have a buffer window of one week (25 March - 1 April) to validate the predictions of our model. In the case of the US, our model captures well the current infected curve growth and predicts a halting of infection spread by 20 April 2020. We test our model predictions in the duration 1 April - 8 April compared to the actual data, and a good agreement is seen. We further demonstrate that relaxing or reversing quarantine measures right now will lead to an exponential explosion in the infected case count, thus nullifying the role played by all measures implemented in the US since mid March 2020.

Codes:


1. Codes for Wuhan, Italy, Korea and USA are in .jl files. They are run through the Julia language.
2. Results are in .pdf files
