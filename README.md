# Modular Q-Learning on a Toy Litter-Gathering Example

A simple toy environment is designed where an agent's goal is to go from any given position on a 2D grid-world and accomplish several goals:

1. Stay on the sidewalk
2. Avoid obstacles
3. Pick up litter
4. Prefer moving forward

Four separate modules are trained independently and the resultant actions from each module are merged using by simply weighting them. 
