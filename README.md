# COMP4434 Group23 Project: Neural Oblivious Decision Ensembles(NODE)
A supplementary code for COMP4434 Group Report.

# What does it do?
1. We reproduce the code from the selected paper(we modified a lot so that it could be run on our machine)
2. Two traditional ML algorithms to do regression
 * Lasso regression 
 * Decision tree
3. Convolutional Neural Networks
4. A Fast-NODE Complex Neural Networks designed by us

# What do i need to run it?
* A machine with some CPU (preferably 2+ free cores) and GPU(s)
  * Running without GPU is possible but takes 8-10x as long even on high-end CPUs
  * Our implementation is memory inefficient and may require a lot of GPU memory to converge

# How do I run it?
1. Clone or download this repo. `cd` yourself to it's root directory.
2. Grab or build a working python enviromnent. [Anaconda](https://www.anaconda.com/) works fine.
3. Install packages from `requirements.txt`
 * We use __torch == 2.2.2__, __cuda == 12.1__ and it works 
 * You will also need jupyter or some other way to work with .ipynb files
4. Run jupyter notebook and open a notebook in `./notebooks/`
 * Before you run the first cell, change `%env CUDA_VISIBLE_DEVICES=#` to an index that you plan to use.
 * The notebook downloads data from dropbox. You will need __1-5Gb__ of disk space depending on dataset.
