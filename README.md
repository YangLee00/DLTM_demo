# DLTM_demo
A simple implementation of paper "A Dual-Scale Lead-Separated Transformer with Lead Orthogonal Attention and Meta-Information for ECG Classification". 

The code is coming.

In order to reproduce the results in the paper, you need to download the PTB-XL dataset at https://physionet.org/content/ptb-xl/1.0.1/, preprocess the data to 100Hz numpy array following the paper "Deep Learning for ECG Analysis: Benchmarks and Insights from PTB-XL", and then run the main ipynb file after modifying your task and database path.

requirements:
pytorch==1.7.1
numpy=1.18.5
pandas==1.4.1
