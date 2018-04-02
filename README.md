# Episode-Pred-InWiSe
Hypotensive Episode Prediction in ICU via Observation Window Splitting.

This project is a development if the In-Window Segmentation (InWiSe) method for time series prediction, which splits a single observation window (last time interval at prediction time) into several sub-windows of equal size. The resulting feature set combines the features extracted from each observation sub-window and we used the Extreme Gradient Boosting (XGBoost) binary classifier to produce an impending episode prediction model from the combined feature set.

## Requirements
* Python 3.5
* Time Series dataset: files of records with variables values at each time unit (see Example Record File file)

![](https://github.com/eladtsur/EpisodePrediction-InWiSe-py/blob/master/CMS_Creative_164657191_Kingfisher.jpg)
