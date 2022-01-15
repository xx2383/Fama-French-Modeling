# Fama-French-Modeling

In this report I will show the process of replicating my six-factor model and the validity of each factor of the model in different industries. 
Six factors were added into the model, including market factor (MKT), scale factor (SMB) and value factor (HML) from Fama French three-factor model. 
And trend factor (UMD), reversal factor (fx_HML), return on equity (ROE). The application scenario of this model is a-share market, and the data used 
is monthly data. The model reproduction process can be divided into the following steps: data processing, factor calculation, model building and industry
comparison. In addition, to check the accuracy of factor data, I compared the factor values calculated by myself (the copied version) with the data provided
by BetaPlus (the classic version). The results show that the factor values of the copied version are highly correlated with the factor values of the classical
algorithm, and there is no significant difference in the value range. Moreover, the effect of the model established by the two kinds of data is similar, 
indicating that the copied version data has a certain accuracy. In terms of industry comparison, we find that the three factors from Fama French have a very
significant explanatory effect on different industries, while the trend factor, reversal factor and roe factor added on this basis bring a small increase 
in the explanatory degree of different industries.
