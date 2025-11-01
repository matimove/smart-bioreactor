#
Specification Document

The specification document must include the following information:

    Which programming language are you using?
    Python
    
    Also, mention any other languages you are proficient into the extent that you could peer-review projects written in them.
    -

    What algorithms and data structures will you implement in your project?
    Algorithms:
    Dynamic Optimization (calculates the optimal baseline solution)
    Evolutionary search algorithm (Genetic algorithm)
    Machine learning (Q-learning (RL))

    Data structures:
    Arrays (2D-tables for state-action values / array representing feeding schedule / Q-tables for policy learning)
    Dictionaries (For bioreactor state representation)

    What problem are you solving?
    Industrial biotechnology uses bioreactors to grow microbes. Feeding decisions strongly impact productivity and 
    finding the optimal feeding schedule is a complex optimization problem. The goal of the project is to compare and create
    an optimal feeding strategy algorithm to maximize biomass production.

    What inputs does the program receive, and how are they used?
    Program inputs include time (length of simulation and timestep duration), Feed rate action space (Different feed level possibilities), Initial conditions of the reactor, Algorithm starting parameters (like learning rate etc.)    

    Output of the program is the optimal feeding strategy produced by each algorithmic techniques and graphs comparing the results.
    
    Expected time and space complexities (e.g., Big-O analysis)
    Dynamic programming O(T*A) (Timesteps * Actions per timestep)
    Evolutionary algorithm (T*G*P) (Timesteps * Generations * Populations)    
    Q-learning O(T*A*E) (Timesteps * Actions per timestep * Episodes)

    List of sources you intend to use:
    Not sure yet on sources, probably wikipedia for the algorithms along with youtube and other websites to help with coding

The Core of Your Project:
Have a microbial fermentation tank simulator using logistic curves and numerical timestep wise simulation. Each timestep different algorithms suggest an optimal feed rate to be added to the next time step and simulation is continued. At the end we can compare which algorithm performed best. Core of the work goes into developing the three different optimization algorithms (DP, GA and Q-learning).

Study program: Bachelor’s in Computer Science (TKT) 
Language used in documentation: English