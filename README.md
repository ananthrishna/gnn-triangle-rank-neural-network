# Layered Local Hidden Variable Neural Network Oracle (Layered LHV-Net)

Code for article "Quantum-informed learning of genuine network nonlocality beyond idealized resources"
https://arxiv.org/abs/2501.08079

There are two sections of code
- the first one includes python notebooks used for testing - a) the standard Layered LHV-Net framework & b) Layered LHV-k-Net frameworks used for studying networks with shared randomness
- the second one is designed for ease, to be run parallely using a cluster (slurm and batch), this includes a batch script to run the same for results. 
- I have added graph segemnts to show the results

You can retrieve the values of the resoponse functions that were found after training the neural network model to replicate the target distribution, and check for it manually. Since if the response function can succesfully replicate the target distribution, then the distribution can be explained local-realistically.

Please download the values from the Gdrive here. And you can find the python notebook file with the code to check if its local realistic here.
