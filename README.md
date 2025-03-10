# OOESP
Simulating lattice models of surface growth

The code and answers to the questions are in the ipynb notebook, while the generated data is in the Numerical simulations folder (in order to gain time each time you run the code). 

## Simulating lattice models of surface growth

In this project, we want to simulate models of surface growth defined on a 1D lattice of size L (lattice spacing is 1). One particle is dropped every $\Delta t = 1$. Starting from an empty lattice, we want to know how the height of particles at each site evolve. But we can imagine multiple rules on how to choose where to add the particle. Here we will simulate two of those models defined by the following set of rules :

### A) Random Deposition with Relaxation (RDR)



*   Drop a particle on a random site
*   If one of the neighbouring sites is lower, move to the lower site
*   If both neighbours are lower :
     - Go to the lowest
     - If they are both at the same height, choose one of the two with probability 1/2





### B) Solid on Solid (SOS)


*   Drop a particle on a random site
*   If the height difference with its neighbours is greater than 1, remove it


