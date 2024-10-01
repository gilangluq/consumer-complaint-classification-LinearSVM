# Consumer Complaint Classification with LinearSVM

This repository contains a machine learning project aimed at classifying consumer complaints about financial products and services into predefined categories. The dataset used for this project consists of real-world complaints, each labeled with a specific financial product. The goal is to train models that can classify future complaints based on their content.

## Project Overview

Consumer complaints provide valuable insights into issues related to financial products and services. In this project, we tackle the supervised text classification problem where each complaint is assigned a label representing a financial product category. The aim is to build predictive models capable of automatically categorizing complaints, which can improve customer service efficiency and regulatory oversight.

### Key Highlights:
- **Text Classification**: A supervised machine learning approach to categorize complaints.
- **Algorithms Used**: 
  - Linear Support Vector Machine (LinearSVM)
  - Multinomial Naive Bayes
- **Goal**: Improve the accuracy of classifying complaints into product categories.

## Dataset

The dataset consists of consumer complaints received about various financial products and services. Each complaint is a text document labeled with a product category such as "Credit card", "Mortgage", or "Bank account". This classification helps organizations and regulatory bodies understand and prioritize issues in different financial sectors.

## Machine Learning Models

We experimented with multiple machine learning algorithms to classify the complaints:

1. **Linear Support Vector Machine (LinearSVM)**:
   - A powerful algorithm for text classification tasks due to its ability to handle high-dimensional spaces.
   - It aims to find a hyperplane that best separates the data into different categories.

2. **Multinomial Naive Bayes**:
   - A popular algorithm for text classification that works particularly well with discrete data.
   - It assumes that the features are conditionally independent given the class label.

## Methodology

1. **Data Preprocessing**:
   - Tokenization and vectorization of text data.
   - Handling of stop words, stemming, and lemmatization.
   - Transformation into a format suitable for machine learning models (e.g., TF-IDF or Count Vectorizer).

2. **Model Training**:
   - Supervised learning using labeled data for training and testing.
   - Performance evaluation using accuracy, precision, recall, and F1 score.

3. **Model Comparison**:
   - Comparison of different algorithms (LinearSVM vs. Multinomial Naive Bayes) to determine the best-performing model for this classification task.

## Usage

To use the code and replicate the results, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/consumer-complaint-classification-LinearSVM.git
