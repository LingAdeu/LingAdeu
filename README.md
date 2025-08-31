![Header](header.png)

## About
Hi, I am a junior linguist with a current interest in computational stylometry, especially authorship attribution. As this area of interest requires a deep understanding of linguistics, statistics, and computational methods, I'm using data science and machine learning to explore my area of interest. 

Currently, I'm learning how to extract important linguistic features from text data and how to experiment machine learning models for text classification. I am also exploring how to apply computational approaches (distance-based and ML-based) to authorship attribution. In addition to these two, I am working on some data science projects in business context to get myself familiar with numbers.


<details>
<summary style='color:grey'>Key Projects</summary>

- **<u>PREDICTIVE MODELING</u>**
  - **Optimizing Ride Fares: A Dynamic Pricing Model for Ride-Sharing Services** (Regression)
    - Currently, ride-sharing prices are primarily set based on ride duration, overlooking fluctuating demand and supply. This project explores a dynamic pricing model powered by machine learning to enhance profitability while keeping prices appealing to customers. By experimenting with 12 machine learning (ML) algorithms and two feature engineering techniques, the project developed a model that, when tested with a simulation of 100 customers, showed that increasing the expected ride duration by 20% through a promotional campaign could generate a net profit of \$2,400. ([Read More](https://github.com/LingAdeu/dynamic-pricing-model.git))  
  - **Addressing Customer Churn in an E-Commerce Company** (Classification)
    - This project seeks to reduce an e-commerce company's customer churn rate from 16.8% to 10%. Using diagnostic analysis and a classification model, we focused on minimizing false negatives due to their higher financial impact. After testing various techniques and algorithms, we chose XGBoost and identified tenure and cashback amount as key factors for intervention. Simulations showed that with targeted strategies, achieving the 10% churn rate can be achieved. ([Read More](https://github.com/LingAdeu/customer-churn-prediction.git))
  - **1-Year Forecasting of Ozone Pollution in Jakarta** (Time Series)
    - Ground-level ozone ($O_3$) in Jakarta is a significant air pollutant, often exceeding safe levels and posing serious health risks like asthma and bronchitis, especially as it reaches 'critical status' nearly twice as often as other pollutants. This project aimed to build a time series model to forecast ozone levels for the next year, helping policymakers understand long-term trends and take timely action. I developed and compared four models, namely ARIMA, AutoARIMA, Prophet, and LSTM, using historical pollutant data from 2010 to 2022. The models were evaluated based on RMSE and their ability to capture long-term trends, with Prophet achieving the best accuracy (RMSE of 13.05 ppm), outperforming the more complex LSTM model. With better forecasts, the Environmental Management Agency can issue early warnings, implement traffic restrictions, and adjust emissions regulations to mitigate health risks. ([Read More](https://github.com/LingAdeu/forecasting-ozone-in-jakarta))
<br>

- **<u>DATA ANALYSIS</u>**
  - **Evaluating Marketing Campaign Effectiveness for New Menu Items: An A/B Testing Approach** 
    - This project assesses which promotional campaign best boosts sales for a fast-food company's new menu items. Statistical analysis, including the Kruskal-Wallis $H$ test and Dunn's post-hoc test, was used due to non-normal sales distributions and outliers. Results showed the first campaign achieved the highest median sales, but the practical difference ($\eta^2$) between campaigns were minor. It is recommended that the Marketing Manager re-evaluate marketing strategies and target customers to improve campaign impact. ([Read More](https://github.com/LingAdeu/ab-testing-campaign-effectiveness.git))
  - **Improving the Number of Review: Exploring Review Patterns in Bangkok's Airbnb Landscape** 
    - Despite an increase in reviews, about 36% (5.7 thousand) of Airbnb listings in Bangkok received none from 2012 to 2022. This project explores why some listings lack reviews and offers recommendations for Airbnb Thailand. It finds that unreviewed listings often have higher prices and longer minimum stays, which may deter bookings and reviews. In contrast, reviewed listings are typically entire homes or apartments, more centrally located, and closer to popular areas. Recommendations include adjusting prices and minimum stays for unreviewed listings, running promotions to boost reviews, and improving marketing to highlight unique features and attractions. ([Read More](https://github.com/LingAdeu/bangkok-airbnb-review-exploration.git))
<br>

- **<u>NATURAL LANGUAGE PROCESSING</u>**
  - **Using Personal Names to Predict Gender: A 3-Character N-Gram Approach**
    - This project investigated whether conventional machine learning algorithms with character n-grams could outperform Long Short-Term Memory (LSTM) models, which achieved an F1 score of 0.93 ([Septiandri, 2017](https://doi.org/10.48550/arXiv.1707.07129)). Using 3-character n-grams focusing on word boundaries to capture spacing between name parts, the Support Vector Machine with a linear kernel performed best, achieving an F1 score of 0.94. The results suggest that conventional models can match or exceed LSTM performance when using word-boundary 3-character n-grams. ([Read More](https://github.com/LingAdeu/predicting-gender-based-on-name))
  - **Understanding User Perceptions about Products on Tokopedia**
    -  Multiple ML experiments are carried out to perform automatic sentiment extractions about customer reviews on Tokopedia (still on progress). The experiments so far have involved conventional ML models, Recurrent Neural Network models, and large language models (LLM). Prior to performing the traditional ML experiment, an exploratory data analysis was done to understand the feature engineering techniques. In short, the first experiment with Support Vector Machine model performed well, surpassing Long Short-Term Memory (LSTM) models, in terms of F1 scores (0.95 vs 0.75). The more recent experiment, implementing base IndoBERT model (uncased) with 110M parameters achieved an outstanding F1 score of 0.98, indicating excellent performance. Judging from these tentative experiment outputs, fine-tuned IndoBERT model is the most promising candidate model in production for the project goal. Not only does IndoBERT have outstanding performance on test set, the LLM predictions can also be explained with various explainable AI techniques, contributing to both good performance and transparency of predictions. ([Read More](https://github.com/LingAdeu/sentiment-model-experiment))
</details>

<div align="left">
  <h3 align="left">My tools</h3>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rstudio/rstudio-original.svg" height="40" alt="rstudio logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" height="40" alt="vscode logo"  />
  <img width="12" />
  <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.svg" height="40" alt="markdown logo"/>
  <img width="12" /> 
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/10/2023_Obsidian_logo.svg" height="40" alt="markdown logo"/>
  <img width="12" /> 
  <img src="https://img.icons8.com/color/48/tableau-software.png" height="40" alt="tableau logo"/>
  <img width="12" /> 
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Postgresql_elephant.svg" height="40" alt="postgresql logo"/>
  <img width="12" /> 
  <img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original.svg" height="50" alt="mongodb logo" />
  <img width="20" />
  <img src="https://cdn.worldvectorlogo.com/logos/docker.svg" height="40" alt="docker logo" />
  <img width="12" />
  <img src="https://huggingface.co/datasets/huggingface/brand-assets/resolve/main/hf-logo.svg" height="50" alt="huggingface logo" />
  <img width="20" />
</div>

<!--
<details>
<summary style='color:grey'>Libraries</summary>
<br>
  <img src="https://icon.icepanel.io/Technology/png-shadow-512/Pandas.png" height="40" alt="pandas logo" />
  <img width="12" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/67/Numpy-svgrepo-com.svg" height="40" alt="numpy logo"  />
  <img width="12" />
  <img src="https://icon.icepanel.io/Technology/svg/Matplotlib.svg" height="40" alt="matplotlib logo" />
  <img width="12" />
  <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" height="40" alt="seaborn logo" />
  <img width="12" />
  <img src="https://icon.icepanel.io/Technology/svg/scikit-learn.svg" height="40" alt="scikit-learn logo"  />
  <img width="12" />
  <img src="https://raw.githubusercontent.com/rstudio/hex-stickers/2b7523c5f8198c98c270c2a7489cbcf67d190cea/SVG/tidyverse.svg" height="40" alt="tidyverse logo" />
  <img width="12" />
  <img src="https://raw.githubusercontent.com/rstudio/hex-stickers/2b7523c5f8198c98c270c2a7489cbcf67d190cea/SVG/quarto.svg" height="40" alt="quarto logo" />
  <img width="12" />
</details>
-->

<div align="left">
<h3 align="left">Connect with me</h3>
  <a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  </a>
  <a href="https://medium.com/@lingostat" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/medium/default.svg" width="52" height="40" alt="medium logo"  />
  </a>
</div>
