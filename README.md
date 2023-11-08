**Method:**

The three R scripts in this repo are used for an analysis of the logistic growth of a bacterial culture. The plot_data script contains code to plot the growth data of the bacteria, making both a graph of all the data, and a graph showing just the start of the logistic growth curve where the Y axis (N) is logged to give a linear relationship where exponential growth is happening. The fit_linear_model script creates two different linear models to allow you to get estimates of parameters needed to plot a curve through the growth data. The first model provides estimates of log(N0) and r by looking at the initial growth rate where it is exponential, and approximates to r. The second model provides an estimate of K as the intercept by looking at the part of the graph where growth has stopped and N approximates to K. The plot_data_and_model script uses the values of these parameters to plot a curve on top of the growth data.


**Results:**

For experiment 3, the estimates of the parameters needed for the model were:

N0 = 5125.585, r = 4.964e-03, K = 4.998e+09

The linear model created mapped closely to the plotted growth data
![image](https://github.com/MatNoble1/logistic_growth/assets/147311707/9ebf9a71-913e-4cae-983e-eb07f582500a)
