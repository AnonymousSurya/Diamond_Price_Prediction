# Diamond Price Prediction Project


There are 10 independent variables (including `id`):
**The dataset** The goal is to predict `price` of given diamond (Regression Analysis).
* `id` : unique identifier of each diamond
* `carat` : Carat (ct.) refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.
* `cut` : Quality of Diamond Cut
* `color` : Color of Diamond
* `clarity` : Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.
* `depth` : The depth of diamond is its height (in millimeters) measured from the culet (bottom tip) to the table (flat, top surface)
* `table` : A diamond's table is the facet which can be seen when the stone is viewed face up.
* `x` : Diamond X dimension
* `y` : Diamond Y dimension
* `x` : Diamond Z dimension

Target variable:
* `price`: Price of the given Diamond.

Dataset Source Link :
[https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv](https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv)



### Task Performed:
* Cleaned the data.
* Executed the Data Preprocessing and Feature engineering.
* Performed Exploratory Data Analysis.
* Used LinearRegression, Lasso, Ridge, Elasticnet & DecisionTree Models for training purpose.
* DecisionTree performed the best with a R2_Score of 0.954
* Created flask app for model
* Deployed it in AWS using CodePipeline & Elastic Beanstalk 



### Run Locally

Clone the project
```
gh repo clone AnonymousSurya/Diamond_Price_Prediction
```
Install dependencies

```
  pip install -r requirements.txt
```
Training model 

```
  python src\pipelines\training_pipeline.py
```

Start the server

```
  python application.py
```


### Screenshots of web app
![Screenshot (138)](https://github.com/AnonymousSurya/Diamond_Price_Prediction/assets/76435009/fa4b1755-7f34-4828-98f8-6b7384b0b955)
