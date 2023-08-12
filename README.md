# Time Series Analysis with LSTM
This project involves performing sentiment analysis on Twitter data using a RandomForest Classifier. The goal is to classify tweets into different sentiment categories. Here's an overview of the project:


## Data Preprocessing

The project begins with data preprocessing, where Twitter training and validation data are loaded. Text preprocessing is performed by converting text to lowercase, removing special characters, URLs, and mentions. The NaN values are handled, ensuring clean and consistent text data.

## Model Development

The sentiment analysis model is developed using a RandomForest Classifier. TF-IDF vectorization is applied to the text data, and sentiment labels are encoded into numerical values. The RandomForest Classifier is trained on the transformed data, and predictions are made on the validation set. The accuracy of the model is calculated and printed.

## Results

The RandomForest Classifier achieved a validation accuracy of 96.40%, demonstrating its effectiveness in classifying Twitter sentiments.


## Installation

Before running the provided code in the notebook, ensure you have the necessary dependencies installed:

-   Python 3.
-   Numpy
-   Pandas
-   Scikit-learn
-   NLTK

You can install these dependencies using the following command:

```bash
pip install numpy pandas scikit-learn nltk` 
```
## Usage

Follow these steps to use the code in the notebook:

1.  Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/your-repo.git` 
```
2.  Download the dataset (`twitter_training.csv` and `twitter_validation.csv`) and place them in the appropriate directory of the project.
    
3.  Launch Jupyter Notebook and open the `sentiment_analysis.ipynb` notebook.
    
4.  Execute the code cells in the notebook sequentially to perform sentiment analysis on Twitter data. The notebook provides detailed explanations of each step.
    
5.  Explore the results and conclusions drawn from the sentiment analysis.

## Acknowledgments

This project draws inspiration from various resources on sentiment analysis and machine learning techniques for text classification.
