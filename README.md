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
1. Data Cleaning
2. Data Preprocessing and feature engineering
3. Exploratory Data Analysis
4. Model training
5. Pickelizing model
6. Creating flask app for model
7. Deployed it in AWS using CodePipeline & Elastic Beanstalk 



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

