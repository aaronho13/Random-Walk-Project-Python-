# Random-Walk-Project (Python)


Summary: This project serves as an introduction and a simplification of a Random Walk. Random Walks is a mathematically derived random process
in which random steps are taken in succession with each other on a mathematical or topological space. These steps can be independent of
each other or have some dependence on the movement of the last step. This project aims to provide a solution and methodology for a 
simplified version of random walks in 1-D and 2-D but can be abstracted and generalized to n-dimensional spaces. 

# Motivation

This was a research project organized by the Society of Physics Students RSO (SPS) at The University of Chicago. It was meant to instruct
students about the uses of Python in mathematical and physical applications. 


# Screenshots

<img width="417" alt="1D" src="https://github.com/aaronho13/Random-Walk-Project-Python-/assets/136650578/ca7dbc50-12c5-416f-a962-ba7e814534ff">

Representation of the Random Walk in 1 Dimension, which can be generated with and without the use of Python's "for loop", both of which methods
are mentioned in the file. However, for efficient programming, the "for loop" generation is not used to generate further Random Walks, due to
the toll and timing of computing higher finite numbers in the "for loop"

Some applications of this Random Walk are as follows: 

<img width="421" alt="Pi estimate" src="https://github.com/aaronho13/Random-Walk-Project-Python-/assets/136650578/7ea357ec-bf63-4ad5-b240-deebb812eb88">

1. Approximating the values of pi, using multiple iterations of random walks of an increasing number of steps per walk. Combining this collection 
of walks with algebraic and mathematical manipulations yields a close approximation of pi. 


<img width="449" alt="Normal Distribution" src="https://github.com/aaronho13/Random-Walk-Project-Python-/assets/136650578/e1029333-bad8-4be7-bbe0-bbe542d359d8">

2. Gaussian (Normal) Approximation of random walks where the number of steps of the walk is fixed. This fixation induces a normal approximation
as seen in the code and the image above. This implies the estimate (by means of probability) of the distance a random walk with a fixed number
of steps is from the origin or starting point. 


<img width="473" alt="2D version" src="https://github.com/aaronho13/Random-Walk-Project-Python-/assets/136650578/d005e2d4-c6fd-46ec-82cc-9eb90dce6bb0">

3. This is a visual representation of 2-D random walks generated and a graph of the associating probability curves. The differences in the standard
deviations of the predicated and theoretical values are discussed in the file and are a result of the simplification process I used to generate
the random walk. However, as mentioned in the code comments, this process can be abstracted and generalized for a more accurate random walk in
2 Dimensions.

# Notes

Finally, this project and its contents can be generalized towards higher dimensions, for example, the third dimension, with appropriate, but fairly similar, edits to the code.


