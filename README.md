# CSC555 - Final Project - Modeling the Spread of Trends Within Various Social Network Distributions

This is a project completed for the Social Computing and Decentralized Artificial Intelligence graduate course at North Carolina State University, completed as a group with Christopher Elchik, Zackary Haugan, and Ethan Telep. We created simulations with adjustable parameters to model the 'Overnight Trend' phenomenon with a graph of autonomous agents, based on real-life social networks.

[Link to paper where we discussed all details of the simulation and our results](https://github.com/ChristopherElchik/Trend-Modeling/blob/f7c9a17567c70e812de6146719e10c5b7220bf41/Modeling%20the%20Spread%20of%20Trends%20Within%20Various%20Social%20Network%20Distributions.pdf)

## Datasets
Facebook Networks (from Stanford's SNAP Lab): https://data.world/socialmediadata/social-circles-from-facebook

## Libraries
Networkx - for graph/network analysis: https://networkx.org/documentation/stable/index.html
Mesa - for agent-based simulations: https://mesa.readthedocs.io/stable/

## Dependencies
```
- Python           : 3.12.5

- IPython          : 8.14.0
- ipykernel        : 6.25.1
- ipywidgets       : 8.1.0
- jupyter_client   : 8.3.0
- jupyter_core     : 5.3.1
- jupyter_server   : 2.7.0
- jupyterlab       : 4.0.5
- nbclient         : 0.8.0
- nbconvert        : 7.7.3
- nbformat         : 5.9.2
- notebook         : 7.0.2
- qtconsole        : 5.4.3
- traitlets        : 5.9.0

- Mesa             : 2.3.4    <-- Note that this isn't the latest version; use this to install on windows: pip install Mesa==2.3.4
- NetworkX         : 3.3
- Numpy            : 1.26.4
- Matplotlib       : 3.9.2
```
## Run Instructions
The results are already committed into the current repository.

To confirm these results, feel free to run locally with the following instructions:

- Ensure all above dependencies are installed
- Open pipeline.ipynb
- Ensure that the relative path of the data files is accurate ('data/socialmediadata-social-circles-from-facebook/original/facebook/[filename]')
- Restart/run all cells
