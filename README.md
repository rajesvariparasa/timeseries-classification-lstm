# Timeseries Classification using LSTM

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rajesvariparasa/timeseries-classification-lstm/blob/main/Timeseries_Classification.ipynb)

This notebook demonstrates timeseries classification for crop identification on a subset of the MiniTimeMatch dataset by training an LSTM model.

The first two sections of this notebook are dedicated to data exploration and setting up a data preparation pipeline using a custom dataset class. The rest of the notebook deals with the set up and finetuning of the model architecture and the training loop.

Briefly about the data: Each observation in the data consists of a time sequence of 52 observations taken across 10 spectral bands of Sentinel-2. Each observation corresponds to spectral measurements aggregated over a land parcel. The observations are labelled with crop found in the parcel.


Data source: [TimeMatch Dataset](https://zenodo.org/records/5636422)
