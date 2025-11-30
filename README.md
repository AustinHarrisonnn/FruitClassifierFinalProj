# Machine Learning Fruit Classifier
This project I used a kaggle fruit_classification dataset to train a ML model that would predict the type of a fruit based
on physical and sensory features such as size, weight, shape, taste, and price.

## Overview
My goal with this project was to build a classification model using traditional machine learning techniques to identify various
fruit types. I used a Random Forest Classifier, performed data preprocessing, EDA, and evaluated the models performance. The 
ending model achieved 100% accuracy as the dataset I used ended up having highly seperable features distinguishing the fruits.

## Dataset
fruit_classification(https://www.kaggle.com/datasets/pranavkapratwar/fruit-classification/data)

The dataset contains 10,000 rows that depict 20 different fruits with columns such as:
- size (cm)
- shape
- weight (g)
- avg_price (₹)
- color
- taste
- fruit_name

## Model and Techniques Used
- Label encoding for categorical features
- Train/Test split (80/20)
- Random Forest Classifier
- Accuracy + Classification report
- Manual sample predictions
- Data Visualizations (bar graph, heatmap, scatterplot, value counts)

## How to run project
````
git clone <your_repo_url>
cd fruit-classification-ML-project
pip install -r requirements.txt
python
````
Then open and run in colab notebook.
