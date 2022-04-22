# SC1015 SC9 Team 09 mini-project assignment
Our team's objective is to make use of the <a href="https://www.kaggle.com/datasets/unsdsn/world-happiness">World Happiness Index</a> data gathered from Kaggle to predict future happiness scores based on the variables included in the dataset. This can then be used as a metric to evaluate certain policy changes in countries or to identify the key aspects that can influence perceived happiness, something which could be used as a talking point for electoral candidates for example.

# Contributors
<ul>
  <li>@hyutake (Kaihang) - Data Cleaning, EDA, Data Visualisation, Regression, LSTM
  <li> Wei Chun - Regression
</ul>

# Libraries used
<ul>
  <li>Pandas
  <li>Numpy
  <li>Seaborn
  <li>Plotly
  <li>Keras
  <li>Scikit-learn
</ul>

# Problem definitionn
<ul>
  <li>Can we predict future Happiness Scores of countries?
  <li>What model is the best in doing so?
</ul>

# Models used
<ul>
  <li>Linear Regression (Multi-variate)
  <li>Recurrent Neural Networks using Long Short Term Memory
</ul>

# Datasets
Dataset used for the project can be found in this folder. It consists of data collected through the World Happiness Report for 2015 - 2019

# Conclusion
<ul>
  <li>GDP has the highest correlation to Happiness Score out of other variables such as Life expectancy, Family, Freedom and Govt. trust.
  <li>Majority of the top 10 happiest countries over 2015 - 2019 are from Western Europe
  <li>Majority of the bottom 10 happiest countries over 2015 - 2019 are from Sub-Saharan Africa
  <li>Multi-variate linear regression performed quite poorly compared to Recurrent Neural Networks
  <li>Although predictions on future happiness scores were quite accurate based on the available data, actual future happiness scores can easily vary with significant events such as the Covid-19 pandemic or the Ukraine war.
</ul>

# What did we learn?
<ul>
  <li>Neural networks, keras and tensorflow
  <li>Plotly graphs that are interactive (rendered in png format to be visualised on GitHub)
</ul>

# References
<ul>
  <li>https://www.kaggle.com/datasets/unsdsn/world-happiness
  <li>https://plotly.com/python/choropleth-maps/
  <li>https://plotly.github.io/plotly.py-docs/generated/plotly.express.choropleth.html
  <li>https://towardsdatascience.com/lstm-framework-for-univariate-time-series-prediction-d9e7252699e
  <li>https://www.youtube.com/watch?v=Mdp5pAKNNW4
  <li>https://www.youtube.com/watch?v=S8tpSG6Q2H0
</ul>
