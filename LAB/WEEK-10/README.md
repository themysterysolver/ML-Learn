### GENETIC ALGORITHM
---
- `GA` is a *optimisation* and *search technique*
- It is heuristic(trail-and-error)
- Works with principle of natural selection and genetics
##### Basic steps
```
1.Encoding of genotypes form phenotype:Population init
2.Fitness assignment
3.Selection
4.Crossover
5.Mutation
6.Survivor selection/replacement
7.Termination
```
---
### TSP:Traveling salseman problem
- **Rules**: Visit every city only once, then return back to the city you started in.
- **Goal**: Find the shortest possible route.
>**In other words:** The shortest possible ***Hamiltonian cycle*** (a closed loop that visits every city once).

- **DSA:** We can provide a solution via a *greedy* algorithm always choosing the nearest city and reaching back to the starting point.
- **GA:** we cna use ga to solve this by giving the path as a list of points.
---
#### TOURNAMNET SELECTION METHOD
Tournament selection is a method for selecting parents from a population in genetic algorithms. The idea is to randomly select a small group (or tournament) of individuals from the population, and then choose the best individual from this group to become a parent.

---