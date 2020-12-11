# Surrounding Motion Predict Model for Autonomous Vehicle



> Wenhao Cui, Guangrui Shen, Tieming Sun
> 
> EE 599 Deep Learning - Fall 2020

<p align="center"><img src="img/output_scene.gif" alt="Scene" width="500" /></p>

## Introduction

-  Predict surrounding agents motions of the autonomous vehicle over 5s given their historical 1s positions
- Useful for planning self driving vehicle’s movement
- Deep learning techniques (CNN: Mixnet) + Ensemble Models
- Choose negative multi-log-likelihood as evaluate metric
- Full Information provided by [Kaggle](https://www.kaggle.com/c/lyft-motion-prediction-autonomous-vehicles/overview/description)

## Run Model
- Follow the instruction on [Lyft Website](https://self-driving.lyft.com/level5/data/) to download Dataset
- Use Jupyter Notebooks under directory "notebook" to run our model
- Or run python script under "code", first changing your path to dataset
- Structure of this repo

```
- code - train.py
      |
       - test.py
      |
       - model.py
      |
       - utils.py

- data_model - pth
            |
             - metric

- notebook - train-cnn-nll.ipynb
          |
           - test-cnn.ipynb
```

## Detailed Report
- Final report and presentation are provided under directory "report"

## Lyft Prediction Dataset
@misc{lyft2020,\
title = {One Thousand and One Hours: Self-driving Motion Prediction Dataset},\
author = {Houston, J. and Zuidhof, G. and Bergamini, L. and Ye, Y. and Jain, A. and Omari, S. and Iglovikov, V. and Ondruska, P.},\
year = {2020},\
howpublished = {\url{https://level5.lyft.com/dataset/}}
}