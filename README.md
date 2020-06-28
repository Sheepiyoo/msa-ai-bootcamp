# MSA AI & Advanced Analytics

## Clickbait Detector

This project implements a 3-layer fully connected network using Keras to predict the probability that a title/headline of an Internet article is clickbait. To train the model and view results, clone the repositiory into an Azure workspace with the default libraries installed and run the notebook final-clickbait in the root directory. The final cell in the notebook allows a user to manually enter a title and retrieve a prediction from the model.

Main dependencies:
- keras: 2.3.1
- matplotlib: 3.2.1
- scikit-learn: 0.20.3
- tensorflow: 2.1.0
- seaborn: 0.9.0

## Dataset:
A file containing 32000 article titles and binary labels for whether it is clickbait.

Github source: https://github.com/bhargaviparanjape/clickbait/tree/master/dataset

Kaggle source: https://www.kaggle.com/amananandrai/clickbait-dataset

Reference paper for dataset source: https://people.mpi-sws.org/~achakrab/papers/chakraborty_clickbait_asonam16.pdf