# Radio-Link-Failure-Prediction
### An ML-based RLF Prediction Algorithm to predict failures in a radio-link wireless communication channel<br/>
Stable and high-quality internet connectivity is mandatory to 5G mobile networks, but once something unexpected happens, the influence of the defect is quite severe. This is due to various weather-related phenomena that affect the performance of radio links like clouds, rain, snow etc. Thus correct radio link failure prediction is necessary to avoid such radio link failures.<br/>

The objective of this problem statement is to predict the occurrence of radio link failures in:
1. in the next day
2. in the following 5 days <br/>

A Machine Learning and Time Series Forecasting model is built for the same. <br/>

The Repository contains the following files:</br>
1. **Training_Validation_Notebook.ipynb**: Python notebook with code for training and validation </br>
2. **final_feature_engineering.ipynb**: Python notebook with code to predict the redundant columns that can be eliminated to improve performance of failure prediction</br>
3. **Training_preprocess.ipynb**: Python notebook to preprocess training data </br> 
4. **validation_preprocess.ipynb**: Python notebook to preprocess validation data </br>
5. **20210125_predicts.tsv**: TSV file containing validation output
6. **20210426_predicts.tsv**: TSV file containing validation output 1
7. **20210525_predicts.tsv**: TSV file containing validation output 2
8. **20210614_predicts.tsv**: TSV file containing validation output 3
9. **20210817_predicts.tsv**: TSV file containing validation output 4

</br>

The problem statement is a part of the **ITU AI for Good Machine Learning in 5G Challenge**. The dataset was provided by Turkcell and can be accessed using the following link: https://github.com/Turkcell/ITU-AIMLin5GChallenge-2021    <br/>
<br/>
Zip file of the dataset contains the following tab separated files (tsv):<br/>
• distances.tsv: pair-wise distances<br/>
• met-forecast.tsv: meteorology 5-day forecasts<br/>
• met-real.tsv: meteorology historic realizations<br/>
• met-stations.tsv: meteorology station information<br/>
• rl-kpis.tsv: radio link KPIs and configuration parameters<br/>
• rl-sites.tsv: radio link site information<br/>
