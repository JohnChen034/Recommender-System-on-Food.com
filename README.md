# Recommender Systems on Food.com Rating

## Overview
This project develops advanced recommender models to improve personalized recipe recommendations on Food.com. The models utilize user reviews and ratings to predict user satisfaction and enhance the browsing experience.

## Project Summary
The project utilizes three main models to predict recipe ratings:
1. **Baseline Linear Regression Model** - Establishes fundamental user and item biases.
2. **Sentiment Analysis Model** - Incorporates sentiment from user reviews to capture emotional feedback.
3. **SVD++ Model** - Uses matrix factorization to uncover deeper, implicit user preferences.

Combining sentiment analysis with SVD++ in an ensemble model, we achieved our best accuracy with an MSE of 0.234, significantly enhancing prediction accuracy.

## Datasets
1. **Raw Recipes Dataset** - Contains 230k+ recipes with details such as cooking time, ingredients, nutrition, etc.
2. **Raw Interactions Dataset** - Includes 1.1 million user interactions (ratings, reviews).

The datasets were merged and cleaned, resulting in 650k entries optimized for predictive modeling.

## Models and Results
- **Baseline Linear Regression** - Achieved an MSE of 0.476.
- **Sentiment Analysis Model** - Improved prediction accuracy, achieving an MSE of 0.341.
- **SVD++ Model** - Leveraged implicit interactions, reaching an MSE of 0.328.
- **Ensemble Model** - Combined Sentiment Analysis and SVD++ for the best performance with an MSE of 0.234.

## Conclusion
This ensemble approach effectively combines quantitative and qualitative data, providing enhanced personalized recipe recommendations and a more satisfying user experience on Food.com. 
