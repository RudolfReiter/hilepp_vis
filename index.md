## Welcome to the project page of "A Hierarchical Approach for Strategic Motion Planning in Autonomous Racing."

This work is related to a [European Control Conference 2023 paper](https://ieeexplore.ieee.org/document/10178143) by Rudolf Reiter, Jasper Hoffmann, Joschka Boedecker, and Moritz Diehl. Moreover, this work was accepted to be presented as a poster at the International Conference on Machine Learning 2024.


An approach is presented for safe trajectory planning, where a strategic task related to autonomous racing is learned within a simulation environment. The following videos show evaluations of the trained HILEPP-II policy in different scenarios related to autonomous racing tasks. Opponent vehicles are simulated with obstacle-avoiding MPC formulations for autonomous racing, which do not explicitly consider strategic driving (PPP)

## Scenario 1: Blocking
The ego vehicle starts first and has to block three stronger opponents. "Stronger" refers to parameters such as vehicle mass, acceleration limits, and available braking force.
<iframe width="1120" height="630" src="https://www.youtube.com/embed/Pp5qHcdNGQw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Scenario 2: Overtake
The ego vehicle starts last and has to overtake three weaker opponents. "Weaker" refers to parameters such as vehicle mass, acceleration limits, and available braking force.
<iframe width="1120" height="630" src="https://www.youtube.com/embed/0yV2myOdsW0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Scenario 3: Mixed
The ego vehicle starts between a stronger following vehicle and a weaker leading vehicle. It has to safely overtake and block the following opponent to achieve a good rank for as long as possible.
<iframe width="1120" height="630" src="https://www.youtube.com/embed/muco3XlAByM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



