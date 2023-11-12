# horse-colic-project


PROJECT DESCRIPTION

This project analyses data on horse colic and creates a classification model to predict colic outcomes. Colic is unpredictable and unpreventable, and unfortunately not an uncommon ailment in equines. Over 70 different intestinal problems cause colic symptons, some of which are life-threatening. 

Using veterinary data on colic patients, the Jupyter notebook ColicAnalysis.ipynb trains a model that determines whether a given patient (horse) is likely to survive or die. 


THE MODEL

A classification model is used (Scikit-learn's HistGradientBoostingClassifier()). This model can handle missing data - it was discovered during the initial cleaning of the dataset that unfortunately many of the features are missing data. Removing the associated features left next to no data for training. To counteract this, the HGBC model was chosen.

A hyperparameter-tuned HGBC model is saved here as fitted_HGBR_model.sav. This model can be loaded in using pickle (see Jupyter notebook for example).

FUTURE IMPROVEMENTS

A future improvement to the project involves modelling the interaction of some of the features in detail.

REQUIREMENTS

The package requirements for the Jupyter notebook are included in the requirements.txt file. 

USING THIS PROJECT

Using this project should be as simple as downloading the repository and running the Jupyter notebook ColicAnalysis.ipynb. The notebook contains markdowns and comments to help users follow the code. 

CREDITS

McLeish, Mary and Cecile, Matt. (1989). Horse Colic. UCI Machine Learning Repository. https://doi.org/10.24432/C58W23.
