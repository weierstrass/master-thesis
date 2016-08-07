#Master's thesis report
Master's thesis I did in 2012 at the Department of Mathematical Sciences at Chalmers Univeristy of Technology, Gothenburg. 

The published report can be found here: http://publications.lib.chalmers.se/records/fulltext/170015/170015.pdf

The C++ code that was developed for the thesis can be found here: https://github.com/weierstrass/wlb

##Abstract
The lattice-Boltzmann method is used to model flow in electrokinetic systems. A modelling
approach based on the coupling of Navier-Stokes, Nernst-Planck and Poisson’s
equation of electrostatics is utilised. Three lattice-Boltzmann methods are formulated
for the three equations respectively.
The method is implemented in C++ with the aim of being high performing. Topics as
locality, instruction pipelines and parallel computing are considered. The implementation
is tested for a number of classic examples with known solutions, e.g. Taylor-Green
vortex flow, an Helmholtz equation and an advection-diffusion situation. The computed
solutions agree well with the analytic solutions.
The physical systems modelled consists mainly of various charged channel flows of
ionic solutions. Electrokinetic effects, such as electroosmosis and the electrovicous effect
are studied. This is done in thin channels where the thickness of the electrical double
layers is comparable to the channel dimension. The electroviscous effect is shown to
slow the flow down and a local minimum is found in the velocity profile for thick enough
double layers. Other more complicated systems are also studied; electroosmotic flow in
a channel with heterogeneously charged walls and flow in a an array of charged squares.
Keywords: lattice-Boltzmann, electrokinetics, electrohydrodynamics, Nernst-Planck,
Poisson-Boltzmann, high performance computing.
