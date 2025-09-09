This is a model of artificial benchmark graphs called "General Modular Graphs". It creates graphs with inbuilt community structure according to user's choice of parameters. The parameters are as follows:

l = number of modules (communities),

nmin = minimum size of a module,

nmax = maximum size of a module,

mu = mixing parameter, which varies from 0 to 1,

ov = number of overlapping nodes,

w  =  a flag if given the graph that is produced is weighted, otherwise unweighted

To run the model first the code need to be compiled as follows:

g++ -std=c++11 general_modular_graphs.cpp -o gmg

Then the executable gmg can be called as follows for weighted networks:

./gmg -l <value> -nmin <value> -nmax <value> -ov <value> -w

For unweighted networks just skip the flag w

If you use this code for research purpose, please cite the following article:

@article{kumar2025general,
  title={General Modular Graphs: a benchmark network model for testing community detection algorithms},
  author={Kumar, Abhinav and Kumar, Pawan and Dohare, Ravins},
  journal={Journal of Ambient Intelligence and Humanized Computing},
  pages={1--15},
  year={2025},
  publisher={Springer}
}
