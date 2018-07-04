# Variationally_learning_grover
Code to recreate plots of Variationally Learning Grover's Quantum Search Algorithm  ( arXiv:1805.09337 )

This files contain the code to produce the plot of the article 
Variationally Learning Grover's Quantum Search Algorithm  	
arXiv:1805.09337

qaoa-grover_alldifferent contains code for comparing QAOA algorithm and Grover's algorithm 
for the search problem given that the angles that define QAOA are all different

qaoa-grover_allequal contains code for comparing QAOA algorithm and Grover's algorithm 
for the search problem given that the angles that define QAOA are all equal (driver and diffusion hamiltonian)

qaoa-grover_diffusordifferent contains code for comparing QAOA algorithm and Grover's algorithm 
for the search problem given that the angles of driver hamiltonian are all equal to $\pi$ and the angles of diffusion hamiltonian are all different

3D-plot contains code for recreating the 3d plot used in the article Variationally Learning Grover's Quantum Search Algorithm using the matrix obtained in the article.

The code is based on the Quantum information toolkit (QIT) library http://qit.sourceforge.net/
