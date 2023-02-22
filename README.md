# Product Defects

# Goals
* Monitor the number of products from a specific factory. 
* Investigate certain attributes of the Poisson distribution.
* Determine how many defective products you would expect to see in a given amount of time.
* Apply what you know about the Poisson distribution on a data set.

# Given
* Number of defects on a given day = Poisson with rate parameter, represents our expected value (lambda).
* lambda = 7 defects per day

# Installation --(must have NumPy and SciPy)
### Note, it's better to work on a new env for each project instead of conda base(root). An alternative solution for low storage —install only what you need for each project on a new env & keep packages minimal on base(root).
## Anaconda CLI:
1. conda create --name myenv
2. conda activate myenv
3. conda install numpy scipy
#### Verify that numpy & scipy are installed correctly. If there are no errors, then numpy & scipy are installed correctly.
4. python 
      * import numpy 
      * import scipy
5. When done: conda deactivate

## Miniconda CLI: 
1. conda create --name myenv
2. conda activate myenv
3. conda install pip
4. pip install numpy scipy
#### Verify that numpy & scipy are installed correctly. If there are no errors, then numpy & scipy are installed correctly.
5. python 
      * import numpy 
      * import scipy
6. When done: conda deactivate

## Take a look at the [Anaconda](https://docs.anaconda.com/anaconda/install/index.html) and [Miniconda](https://docs.conda.io/en/latest/miniconda.html) docs for more!
