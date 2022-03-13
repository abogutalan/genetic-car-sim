# Genetic algorithm

- Is an optimization strategy that mimics natural selection
- Solves Knapsackck problem 
- Generate genome one solution (list of 1s and 0s)
- Mutation step is a simple swap
 

##### POPULATION SIZE EFFECT
> If algorithm continuously get stuck on poor solution
- We have low genetic diversity because our population of solutions is so low.
- Overtime they really star to look more and more like each other
and they are kind of unable to break out that optimal solution.
- We can mitigate that by increasing our population size 

##### MUTATION EFFECT
- Increasing the mutation will prevent algorithm to get stuck 
even tho we don't converge on a great solution very quickly.
- Mutation really helps us to explore more of the solution space 
and try to continue finding a good solution. 