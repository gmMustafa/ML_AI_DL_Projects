# Sentiment Analysis with LSTMs

This project uses the IMDB dataset to analyze the sentiment of movie reviews (positive/negative) using Long Short-Term Memory (LSTM) networks.

## Tasks
1. Load the IMDB movie reviews dataset.
2. Preprocess the text data (tokenization, padding).
3. Build an LSTM network for sentiment analysis.
4. Train and evaluate the model.

## Key Questions
1. What is the model’s accuracy in predicting sentiment?
2. How does the choice of hyperparameters affect the model's performance?

## Instructions
1. Open the `Sentiment_Analysis_with_LSTMs.ipynb` notebook.
2. Run the cells to load the data, preprocess, build the LSTM, train the model, evaluate the model's performance, and experiment with different hyperparameters.

## Results
- **Test Accuracy of Initial Model**: Achieved accuracy on the test set after training the initial LSTM model.
- **Test Accuracy of Modified Model**: Achieved accuracy on the test set after modifying the LSTM architecture.
- **Analysis**: Comparison of performance between different architectures and insights into how hyperparameter modifications impact classification accuracy.

## Dependencies
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

You can install the necessary dependencies using the following command:
```bash
pip install tensorflow keras numpy matplotlib
