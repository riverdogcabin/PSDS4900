# Data Science Capstone Project

This Data Science Masters Degree Capstone project was an attempt to find a regression-based model capable of accurately predicting average hourly wind speed at my personal weather station given weather readings from stations in the surrounding area. 

Models use data gathered from personal weather stations in my surrounding area obtained via [Weather Underground's API](https://docs.google.com/document/d/1eKCnKXI9xnoMGRRzOL1xPCBihNV2rOet08qpE_gArAY/edit). Data was obtained via [weekly pulls](wunderground_weekly_pull.ipynb) and, when necessary, via [targeted pulls by station and date range](wunderground_retrieve_observations_by_date.ipynb). 

Various permutations of ten different regression models were assessed; resulting in twenty-two total trials. A summary of methodology and findings may be seen in the [Final Presentation](PSDS4900Capstone.pptx.pdf) and details can be found in the [Final Paper](PSDS4900%20Capstone%20Final.pdf). 

All coding was done in Google Colabratory notebooks in Python 3. Modeling was primarily done using Scikit Learn with visualizations via Matplotlib. Model experimentation and comparison can be found in [wu_observation_modeling.ipynb](wu_observation_modeling.ipynb). The best model and hyperparameters were then chosen and model parameters were saved and used in [wu_predict_observations.ipynb](wu_predict_observations.ipynb) to make the prediction.
