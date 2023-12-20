# MNIST Softmax Regression

## Overview

This project focuses on the analysis and prediction of handwritten digits using softmax regression with the MNIST dataset. The trained model is saved as `FedaratedModel.h5`.

## Implementation

The core implementation can be found in `softmax.py`. This file contains the code for training the softmax regression model on the MNIST dataset.

### Model Saving

The trained model is saved as `FedaratedModel.h5` after training. This file can be used for future predictions or as a starting point for further model development.

## User Interface

The user interface is implemented using Streamlit, and the pages are organized within the `pages` folder. Users can interact with the trained model through these Streamlit pages.

### Running the UI

To run the Streamlit application, execute the following command:

```bash
streamlit run pages/app.py
python softmax.py
streamlit run pages/app.py
