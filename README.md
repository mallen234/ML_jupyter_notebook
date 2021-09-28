# Example Machine Learning Jupyter Notebook

Project1:
Project1 is a notebook that uses a few different ML algorithms to classify a dataset. The dataset are the measurements from a simulated particle collider experiment - specifically an electron positron inelastic scattering. This was a Uni assignment so the first section details the task however no sample code was given to actually create the functioning code. The aim was to try and correctly predict the particle being created in the collision by the various measurement data. Various tests were run with different decision trees to understand how accurate they can be with differing input parameters, max depths and estimators. Then a number of neural networks were used. A shallow model was run and then an investigation into how differing deep models might help was completed. A potential idea for a VAE is detailed and I may come back to this idea and try to complete it.

Project4:
Project4 is a notebook detailing the methods used to reduce background data when the signal data is significantly smaller. At first a series of simple cuts are applied to the data and it is shown that this is not enough to reduce the backgroud to a level where a H0 hypothesis is statistically ruled out ie the probability of a type 2 error is very high.
After this original fitting a NN is employed to reduce the background, by using a NN background data can be sifted for with much higher accuracy than simple square cuts and so the background can be reduced to the level that a signal can be picked out.
