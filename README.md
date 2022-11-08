# Partial-Dependent-Plots-Individual-Conditional-Expectation-Plots
Individual Conditional Expectation (ICE) plots display one line per instance that shows how the instance's prediction changes when a feature changes. The Partial Dependence Plot (PDP) for the average effect of a feature is a global method because it does not focus on specific instances, but on an overall average.

<1> Partial dependence plots (PDPs) show the dependence between the target function and a set of features of interest, marginalizing over the values of all other features (the complement features).
Due to the limits of human perception, the size of the set of features of interest must be small (usually, one or two) thus they are usually chosen among the most important features.

<2> Similarly, an individual conditional expectation (ICE) plot shows the dependence between the target function and a feature of interest. However, unlike partial dependence plots, which show the average effect of the features of interest, ICE plots visualize the dependence of the prediction on a feature for each sample separately, with one line per sample. Only one feature of interest is supported for ICE plots.
