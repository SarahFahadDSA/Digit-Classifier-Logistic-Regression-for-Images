# Digit Classifier: Logistic Regression for Digits

## Overview
This project demonstrates how Logistic Regression can be used to classify handwritten digits from blurred 8x8 grayscale images. Using a dataset of 1797 images, the model learns patterns from training data and predicts unseen digits with high accuracy.

## Dataset
- **Total images:** 1797  
- **Image size:** 8x8 pixels (flattened to 64 features)  
- **Classes:** 10 digits (0–9)  
- **Labels:** One per image  

## Training & Testing
- **Training set:** 1383 images  
- **Test set:** 414 images  
- The model is trained to capture distinguishing features of each digit and evaluated on the test set.  

## Model Performance
- **Algorithm:** Logistic Regression  
- **Accuracy:** ~95%  
- **Evaluation tool:** Confusion matrix to visualize correct predictions and misclassifications  

## Confusion Matrix Insights
- Diagonal entries show correct classifications  
- Off-diagonal entries highlight errors  
- Lighter cells indicate more occurrences; darker cells indicate fewer or none  

## Learnings
- Logistic Regression is effective for simple image classification tasks  
- Confusion matrices provide intuitive insight into model behavior  
- Even with small, blurred images, supervised learning can achieve strong results  

## Technologies Used
- **Python** – Programming language  
- **scikit-learn** – Machine learning library for model building  
- **NumPy** – Numerical computations  
- **Matplotlib** – Data visualization, including confusion matrix  

I’m sharing this project for anyone who wants to learn how to build a logistic regression model. It provides a clear and practical example of using Python for real-world data science tasks. Enjoy exploring! ❤️

