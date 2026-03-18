# MLBD3
# M22AIE216_CSL7110_Assignment3
# Movie Recommendation System

This project implements different types of recommender systems using the MovieLens dataset.
It includes content-based, collaborative filtering, matrix factorization, hybrid models, neural networks, reinforcement learning, and explainability techniques.


## Features Implemented

* TF-IDF based content recommendation
* User profile based recommendation
* User-based and item-based collaborative filtering
* Matrix factorization (SVD)
* Surprise library SVD
* Hybrid recommendation (meta-learning model)
* Neural network based recommender
* Reinforcement learning (Bandit + Q-learning)
* Explainability using SHAP, LIME, and k-NN


## Dataset

MovieLens (ml-latest-small) dataset:

* movies.csv
* ratings.csv


## Requirements

Install the following Python libraries:

```
numpy
pandas
scikit-learn
scipy
tensorflow
scikit-surprise
shap
lime
```

Install using:
```
pip install numpy pandas scikit-learn scipy tensorflow scikit-surprise shap lime
```


## How to Run

1. Download the MovieLens dataset
2. Place dataset files in your project folder
3. Run the notebook or script step by step
4. Make sure paths to CSV files are correct


## Notes

* Some parts (SHAP, neural network) may take time to run
* Surprise library may need Python ≤ 3.11
* Restart kernel after installing new libraries


## Output

* Movie recommendations for users
* Predicted ratings
* Evaluation metrics (RMSE, Precision@K, Recall@K)
* Explanation of recommendations


## Summary

This project compares multiple recommendation approaches and shows how hybrid and learning-based models improve performance over basic methods.
