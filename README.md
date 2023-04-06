# Stellar Object Classification

---

## Description

### The Data

This dataset contains 100,000 observations taken by the Sloan Digital Sky Survey (SDSS). Each observation is either a star, galaxy, or quasar. 

**Source:** https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17

### The Problem 

Based on light characteristics, can we easily classify a stellar observation as a star, galaxy, or quasar?

### The Stakeholders

The stakeholders are a small astronomy company performing similar work but without the proper means to verify the nature of their observation. They only have the ability to gather light data but not the ability to classfify it. So, they'd need to rely on machine learning as a means of classification.

## Insights

### Infrared Insight

<p align="center">
  <img src="/assets/IR_Viz.png" width="60%" height="60%">
</p>

A stellar observation that has a higher than average amount of infrared light is more likely a quasar. Stars and galaxies, on average, have less infrared light.

### Red Shift Insight

<p align="center">
  <img src="/assets/RS_Viz.png" width="60%" height="60%">
</p>

A stellar observation that has a higher than average red shift in its light is highly likely a quasar. Stars, on average, don't have much observable red shift while galaxies do, but not as much as quasars.

## ML Modeling

The model I chose for my stakeholders is a tuned XGBoost Classifier. The following are it's metrics:
<div style="margin-left: auto; margin-right: auto; width: 30%">

|Metric   |Score|
|---------|:-:|
|Accuracy |98%|
|F1       |Galaxy: %, Quasar: %, Star: %|
|Precision|Galaxy: %, Quasar: %, Star: %|
|Recall   |Galaxy: %, Quasar: %, Star: %|

</div>

## Recommendations
