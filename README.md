Linear dynamic programming for the London Underground

Objective: Designed and implemented linear programming models to analyze passenger flow capacity and optimize transportation efficiency on the London Subway network using station and connection data.

Key Contributions:

Maximum Flow Analysis:
Constructed a network of subway stations with arcs representing direct connections and assigned capacities based on randomly generated values for individual lines.
Solved a maximum flow problem to compute the average passenger capacity from King's Cross St. Pancras (#145) to Hammersmith (#110).
Evacuation Optimization:
Restricted the network to specified stations and arcs to model evacuation scenarios.
Computed maximum flow over time for a time horizon of 18 minutes between King's Cross St. Pancras (#145) and Victoria (#273).
Passenger Flow Restrictions:
Incorporated security constraints limiting transit to a maximum of 20 passengers at Oxford Circus (#192) and Embankment (#87).
Solved the adjusted maximum flow problem under these additional restrictions.
Network Improvement:
Developed a linear program to allocate a limited budget of additional capacity across the network.
Optimized improvements to maximize flow between King's Cross St. Pancras and Hammersmith.
Technical Skills:

Applied linear programming techniques using Python and Gurobi.
Designed and analyzed complex networks with capacity constraints and time restrictions.
Modeled optimization problems involving passenger flow and resource allocation.
Outcome: Provided actionable insights for optimizing subway network capacity and enhancing evacuation planning, showcasing the potential for data-driven improvements in urban transit systems.
