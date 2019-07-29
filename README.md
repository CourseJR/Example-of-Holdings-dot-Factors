# Example-of-Holdings-dot-Factors
This is an example of using dot product in portfolio management

The matrix named factors is a pandas DataFrame with rows and columns of assets and risk/alpha factors, respectively. The vector has a size of Nx1, where N is for the assets.  These are holdings that are optimized by determining the minimum cost of the objective function.  In addition, from the objective function, the updated holdings from the previous trading day are determined by using the gradient of the objecive function.  The result of the dot product between the matrix of factors and holdings represent the portfolio exposures.
