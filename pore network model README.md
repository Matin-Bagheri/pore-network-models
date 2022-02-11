# pore-network-models
includes my python codes for pore network modeling and calculation of apaernt permeability
use .py file on local machine or any python interpreter; use .ipynb file on colab platform or jupyter.

the program is originally written for incompressible fluid flow through porous media; in case of special flow conditions, change the mass flux function as 
suits your model; gas flow equations are provided in comments in the mass flux function as well.

this model uses Gaussian distribution for pore throat radius and length; you can change that in the definition of R, L.

please note that the program does not consider the pore sizes in matter compaired to the overall size of throats; thus each node in the pore network is the 
juction of its surrounding throats.

it should also be noted that the model assumes cylindrical throats with random distribution of radius and lengths; in case of a more complex system, apply shape
factors to the model.
