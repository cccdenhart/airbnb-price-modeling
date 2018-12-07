# About
This is my final project for DS4400 (Machine Learning 1).  I use Airbnb data provided by InsideAirbnb.com to explore causal relationships, predict listing attributes, and generate a price optimization tool. 

# Requirements:
* Python 3
* Jupyter Notebooks
* Scikit-Learn
* Tensor-Flow
* Keras
* Numpy
* Pandas
* Seaborn

# Running Instructions:
You must have a folder named 'data' in the top of the project directory in order for .csv files to be properly created by the notebooks
You should also have a folder named 'plots' in the top of the project directory in order to store any plots generated

Notebooks should be run in the following order:
1. collection.ipynb (retrieves and aggregates all data from insideairbnb.com)
2. visualizations.ipynb / review_scores.ipynb / prof_status.ipynb / neighborhood.ipynb (generates visualizations or trains predictive models using initial data)
3. price_changes.ipynb (converts initial calendar data to a richer data set including average daily revenue changes resulting from every price change per listing)
4. optimal_price.ipynb (attempts to predict whether a price change for a given listing will have a negative impact, a positive impact, or no change)
