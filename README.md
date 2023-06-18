# Amazon Reviews Classifier

This project is an Amazon reviews classifier that uses PySpark, a powerful distributed computing framework for big data processing. The classifier is trained on a dataset of Amazon reviews and can predict the sentiment (positive, negative or neutral) of a given review.

## Prerequisites

To run this project, you need the following dependencies:

- Python (version 3.11.1)
- PySpark (version 3.3.1)

## Getting Started

To get started with this project, follow the steps below:

1. Clone this repository to your local machine:

```
git clone https://github.com/AGMach7/AmazonReviewsClassifier.git
```

2. Navigate to the project directory:

```
cd AmazonReviewsClassifier
```

3. Download the Movies and TV dataset from the following link: https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/.
  
4. Open the Jupyter Notebook file `AmazonReviews.ipynb` using Jupyter Notebook:

```
jupyter notebook AmazonReviewsClassifier.ipynb
```

5. Follow the instructions provided in the notebook to train and evaluate the classifier.

## Model

The model architecture and training code can be found in the Amazon_Reviews_Classifier.ipynb notebook. The classifier utilizes logistic regression and random forest classifiers from the pyspark.ml.classification module to train on the Movies and TV dataset.

## Results

The evaluation results of the trained classifiers are as follows:

- Logistic Regression:
  - Accuracy: 86.49%

- Random Forest Classifier:
  - Accuracy: 83.35%

These accuracy values represent the proportion of correctly classified instances out of the total number of instances in the dataset.

Please note that the accuracy values mentioned above are specific to the Movies & TV dataset used in this project and may vary depending on the dataset and training settings.
