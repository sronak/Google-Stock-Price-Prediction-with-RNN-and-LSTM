# Google Stock Price Prediction using LSTM
This project uses a Long Short-Term Memory (LSTM) Recurrent Neural Network (RNN) to predict the stock price of Google using past stock prices.

## Dataset
The dataset used in this project consists of Google's stock prices between March 2014 and March 2023. The dataset is divided into a training set, which contains stock prices from March 2014 to February 2023, and a test set, which contains stock prices for Month March 2023.

## Model
The LSTM RNN is a type of neural network that is well-suited for making predictions based on time-series data. The model consists of four LSTM layers with dropout regularization, followed by a single dense layer that produces the output.

## Results
The model was trained for 100 epochs using a batch size of 32. The predicted stock prices for the month of March 2023 were compared to the actual stock prices, and the results were visualized using a line graph. The model achieved an accuracy of 94% in predicting the trend of the stock prices.

## Files
- **training_set.csv-**: Contains the training set data
- **test_set.csv-**: Contains the test set data
- **stock_price_prediction.py-**: Python script for training the LSTM RNN model and making predictions
- **README.md-**: Project description

## Libraries Used
- numpy
- pandas
- matplotlib
- sklearn
- tensorflow

## Instructions for Running the Code
- Clone the repository.
- Install the required libraries using ```pip install -r requirements.txt.```
- Run the Python script ```stock_price_prediction.py.```
- The predicted stock prices and the actual stock prices will be displayed on a graph.

## Future Work
Experiment with different hyperparameters to improve the accuracy of the model.
Use additional data sources, such as news articles and social media data, to improve the predictions.
Apply the model to other stocks and evaluate its performance.
