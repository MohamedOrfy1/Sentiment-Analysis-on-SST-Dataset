# Sentiment-Analysis-on-SST-Dataset
Text classification into five distinct classes using the Stanford Sentiment Treebank (SST) dataset. The task involves employing two different classification approaches: Naive Bayes and Logistic Regression. Additionally, there is a third part dedicated to evaluation, where we will generate a confusion matrix and derive performance metrics from it.
### Project Structure

* **Assignment 1.ipynb:** Jupyter Notebook containing the code for data loading, preprocessing, model training, and evaluation.
* **README.md:** This file provides an overview of the project.

### Data

The project uses the SST dataset, which contains movie reviews labeled with sentiment scores ranging from 0 (very negative) to 1 (very positive). The dataset is split into training, validation, and test sets.

### Methodology

1. **Data Preprocessing:**
    * Sentiment scores are categorized into five classes: very negative, negative, neutral, positive, and very positive.
    * Bigram features are extracted from the text data.

2. **Model Training:**
    * **Logistic Regression:** Both a custom implementation and scikit-learn's `LogisticRegression` model are trained.
    * **Naive Bayes:** Both a custom implementation and scikit-learn's `MultinomialNB` model are trained.

3. **Evaluation:**
    * Confusion matrix, precision, recall, and F1 score are calculated for each model.
    * The performance of custom implementations is compared with their scikit-learn counterparts.

### Dependencies

* `datasets`
* `numpy`
* `pandas`
* `scipy`
* `matplotlib`
* `seaborn`
* `sklearn`

### Instructions to Run

1. Clone or download the repository.
2. Install the required dependencies.
3. Open the `Assignment 1.ipynb` notebook and run the code cells.

### Notes

* This project is for educational purposes and demonstrates the implementation of Logistic Regression and Naive Bayes for sentiment analysis.
* The performance of the models can be further improved by exploring different feature engineering techniques and hyperparameter tuning.
