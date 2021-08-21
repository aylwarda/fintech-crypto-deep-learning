# fintech-crypto-deep-learning

This project is part of my Fintech homework in which I use a deep learning model to predict the price of bitcoin, given pricing data and sentiment analysis as an indicator (in ML terms, an additional feature).

---
## Instructions / Intro

This Project consists of two Jupyter Notebooks, both of which run through a sequence of steps to prepare the data and then use the model to predict closing prices of Bitcoin.  

In order to make best use of this project, either:
- Read through the conclusions drawn from the experiments within this document and then work through each of the Notebooks ... or
- Work through the Notebooks, draw your own conclusions and contrast with those drawn below.

### Terms
- RNN:  Recurrent Neural Network - an aritificial neural network in which the output of a node becomes an input into the next.
- LSTM: Long Short Term Memory - a term describing this specific recurrent neural network (RNN) model, i.e. LSTM, which overcomes the short term memory problem; a well known problem with "traditional" RNNs.
- FNG: Crypto Fear and Greed Index - an index, made available through an API by the wonderful folks at alternative.me (see more below).

### Notebooks
- [`lstm_stock_predictor_closing.ipynb`](lstm_stock_predictor_closing.ipynb) - a Notebook that looks at closing prices only.
- [`lstm_stock_predictor_fng.ipynb`](lstm_stock_predictor_fng.ipynb) - a Notebook that looks at *both* fear and greed sentiment as well as closing prices.

To run through either Notebook, load it up in Google Colab or Jupyter Labs and run through it, looking at the data prep, the model building, execution and final visualisations.

---
## Deep Learning Model
Both Notebooks explore the use (or benefits) of using .

### Techniques Used

**LSTM with closing price data only**  
This ....  

**LSTM with sentiment analysis and closing price data**  
This ....  

---
## Acknowledgements
### Sources
- More on the FNG index found [here](https://alternative.me/crypto/fear-and-greed-index/)
- Both "Starter Notebooks" provided by Trinity College as part of course work, which are built upon.
- The Keras Deep Learning Library was used; find more [here](https://keras.io/about/).
- TensorFlow is the open-source machine learning platform upon which Keras is built. 

### Licenses
N/A