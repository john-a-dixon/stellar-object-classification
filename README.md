# Project 2

> _**Note:** This repository will change names as soon as the dataset is chosen and approved._

## First Choice Dataset

- **Source:** https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17
- **Description:** This dataset contains observations of space objects and their spectral information.
- **Number of rows:** 100000
- **Row meaning:** Each row is an observation of a space object that is potentially a star, galaxy, or quasar object.
- **Target:** Class; this is the class of the celestial object I want to predict.
- **Features:** There are 18 columns/features, but as of now I'll only use 11 within the feature matrix. This may change over the course of the project.
- **Classification or regression?:** This is a classification problem since I will be trying to predict a category.
- **Challenges:** Honestly, the main challenge I can foresee is understanding the meanings of the columns. This shouldn't be hard at all.

## Second Choice Dataset

- **Source:** https://www.kaggle.com/datasets/ruthgn/beer-profile-and-ratings-data-set?select=beer_profile_and_ratings.csv
- **Description:** This dataset contains stats about beers that relate to their flavor profile and overall rating from a popular beer enthusiast website _BeerAdvocate_.
- **Number of rows:** 3198
- **Row meaning:** Each row is a unique beer.
- **Target:** Style; this is the type of beer I want to predict.
- **Feature count:** There are 25 columns/features, but as of now I'll only use 20 within the feature matrix. This may change over the course of the project.
- **Classification or regression?:** This is a classification problem since I will be trying to predict a category.
- **Challenges:** The main challenge I forsee is unbalanced classes within the target. Some beers are more popular than others. Because of this, I believe there may be more of one class than another within the target. Additionally, since there are many beers in the world, it's possible the target may not be representative of every single type of beer. So, the resultant model may not be able to handle beers it has never seen. This is easily fixable by getting data on different beers, which can be done in the future.
