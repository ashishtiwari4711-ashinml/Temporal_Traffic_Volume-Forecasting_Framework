# Simple RNN Time Series Forecasting

Author: Ashish Tiwari  


---

##  Project Overview

This project implements a **Simple Recurrent Neural Network (Simple RNN)** to perform **single-step time series regression**.

The goal is to predict the *next value* in a sequence using historical data.

Multiple experiments were conducted to study:

- Effect of **data standardization**
- Impact of **RNN hidden units**
- Influence of **batch size**
- Training stability vs performance

The project follows a complete machine learning pipeline:

Data → Preprocessing → Windowing → Model Training → Evaluation → Experiment Comparison

---

##  Why Simple RNN?

Simple RNN is the most basic recurrent neural network architecture.

It:

- Processes sequences step-by-step  
- Maintains a hidden state (memory)  
- Learns temporal dependencies  
- Is computationally lighter than LSTM/GRU  

This project intentionally uses Simple RNN to understand **core sequence modeling concepts** before moving to advanced architectures.

---

##  Pipeline Architecture

1. Load time-series dataset  
2. Split into training and validation sets  
3. Apply preprocessing (standardized vs raw)  
4. Convert series into supervised learning windows  
5. Build Simple RNN regression model  
6. Train with different hyperparameters  
7. Evaluate using MAE, MSE, RMSE  
8. Compare experiments  


