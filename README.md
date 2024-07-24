# LSDF
C1-C10 are csv files containing experimentally determined predator-prey population data from a chemostat experiment. Data available for download at: https://figshare.com/articles/dataset/Time_series_of_long-term_experimental_predator-prey_cycles/10045976/1

Data_load.jl can be used to visualize the initial data. 

Model1.jl is the model for population dynamics generated by Blasius et al., who obtained the data experimentally. They used a wavelet transform. The program should output figures for model performance, and population extrapolation- some issues with that currently

Model2.jl is a hybrid-NODE model, which integrates a neural network into the lotka-volterra equations in order to account for extra complexity in the population dynamics.

Model3.jl is a standard lotka-volterra model. -All model files should show example population cycle predictions, but may not due to bugs/incompleteness.
>>>>>>> f6082a9 (trying to get readme to update)
