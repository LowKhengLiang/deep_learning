# Deep Learning personal projects with Python
# 1) Pro Wrestling Gender Prediction
- The objective is to detect the gender of the wrestler given the other parameters.
- Exploratory data analysis was performed followed by encoding categorical features and dropping irrelevant ones.
- A simple neural network classifier with 1 hidden layer is designed and compared with a Naive Bayes classifier.
- The parameters of the neural network algorithms are adjusted to obtain a result similar or better than the Naive Bayes classifier.
  
# 2) Cat vs Rabbit Image Classification
- The objective is to detect whether an image from the dataset is a cat or a rabbit.
- Exploratory data analysis was performed and a random sample of 6 cat and rabbit images are shown.
- A CNN with 3 dense layer was employed using the tanh activation function and MaxPooling.
- 18% of the training dataset was used for validation and at least 10 epochs was used.

# 3) Stock Price Prediction (DBS Holdings)
- Downloaded 8 years of data up to the last working day of December 2021 for training.
- Downloaded data from 1st working day of 2022 till last working day of 2022 for testing.
- Used previous 52 days of stock information (High and Volume) to predict the next day stock price (High).
- Designed a LSTM with a cell state of at least 100 dimensions and did at least 50 epochs of training.
  
