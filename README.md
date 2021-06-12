# CS235Project
Given the “Huge Stock Market Dataset” sourced by Kaggle, use Fourier transform, DTW, PCA and Recommender Systems using KNN Clustering to forecast and recommend stock options to users to assist them in optimizing portfolio value.

## Fast Fourier Transform (FFT) Notebook
`FourierTransform.ipynb`

This notebook uses FFT to analyze the apple stock series and uses the frequencies to predict 100 days worth of data

## K-Means Notebook
`clustering.ipynb`

This notebook uses k-means clustering to analyze the relationship between stocks to allow for a recommender system for diversifying or specializing a portfolio.

## Recurring Neural Network Notebook
`BestOutcome(2008)-10days.ipynb`

Stuffs...

## Dynamic Time Warping Notebook
`DynamicTimeWarping.ipynb`

This notebook uses DTW to compare two time sequences that do not line up perfectly from the Apple stock series. It calculates the optimal matching between two sequences, by returning a sum difference distance between the two series. We use this information to populate series that will yield the best return.
