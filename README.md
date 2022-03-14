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

### Notes
##### Uniform crossover
- In uniform crossover, typically, each bit is chosen from either parent with equal probability. Other mixing ratios are sometimes used, resulting in offspring which inherit more genetic information from one parent than the other. In a uniform crossover, we don’t divide the chromosome into segments, rather we treat each gene separately. In this, we essentially flip a coin for each chromosome to decide whether or not it’ll be included in the off-spring. We can also bias the coin to one parent, to have more genetic material in the child from that parent.


### Outputs
Experiement Note: Demo mate2ptCrossover method with n=3 
Filename:  demo1.txt
Max distance travelled:  169.3373565673828
Min distance travelled:  -2.2915486097335815

Experiement Note: Demo mate2ptCrossover method with n=10 
Filename:  demo2.txt
Max distance travelled:  188.0631561279297
Min distance travelled:  -2.387052536010742

Experiement Note: Demo mate1ptCrossover method with n=3 
Filename:  demo3.txt
Max distance travelled:  151.1476287841797
Min distance travelled:  -1.441699892282486

Experiement Note: Demo mate1ptCrossover method with n=10 
Filename:  demo4.txt
Max distance travelled:  152.742431640625
Min distance travelled:  -1.2892568707466125

##### Random ideas
- cut it off when the gains between generations are lacking
which happens fairly early, at least in my testing so far

- modifying total_attributes

##### Resource
https://en.wikipedia.org/wiki/Crossover_(genetic_algorithm)
