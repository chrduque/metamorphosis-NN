## METaMorPHosis-NN: METallicity for M dwarfs using PHotometry and Neural Networks

This repository contains the Python code for estimating photometric metallicities of M dwarfs using a neural network approach, as described in **Duque-Arribas et al. (2025)** – *accepted for publication in A&A*.

A Jupyter Notebook is provided with all the necessary code to run METaMorPHosis-NN. The code:  
- Imports the required libraries  
- Loads the trained Keras model (*metamorphosisNN.keras*)  
- Defines the functions used to compute the metallicity predictions  

At the end of the notebook, you’ll find example data for two stars (HD 18143C and HD 20727B). Running the notebook should yield an output similar to:  
\--------------------------  
Results:  
\--------------------------  
[Fe/H] =  0.15 +- 0.04 dex  
[Fe/H] = -0.28 +- 0.08 dex  
\--------------------------  

If your results are similar (note that we rely on Monte Carlo simulations), you're all set to apply the model to your own data!
