# Probabilty & Statistics notes
-

### Chapter 1: Introduction to Statistics and Data Analysis
***

**Terms:**

Name  | Description
----- | -----------
Simple random sampling | any particular sample of a specified sample size has the same chance of being selected as any other sample of the same size. 
Sample size | the number of elements in the sample
Treatments | the populations to be studied or compared in some sense 
Estimate | sample mean
Fundamental assumption | upon which the resulting statistical inference is based
observational study | a kind of study without factor control
retrospective study | study uses strictly historical data, data taken over a specific period of time



**Keywords:**

```
biased sample, experimental design, variability,
experimental unit, completely randomized design,
process variability, population parameters, population mean, population variance, postulated model, Gaussian distributions, regression model, estimation theory, exploratory data analysis, violation of assumptions, stem-and-leaf plot, relative frequency distribution, box-and-whisker plot, outlier
```

**Literal Definitions:**

* The sample along with iinferential statistics allows us to draw conclusion about the population, with inferential statistics making clear use of elements of probability.
* Elements in probability allow us to draw conclusions about characteristics of hypothetical data taken from the population, based on known feature of the population.

-
### Chapter 2: Probability

***

**Terms:**

Name  | Description
----- | -----------
Categorical data | be classified according to some criterion
observation | recording of data
Experiment | any process that generates a set of data
Sample space | The set of all possible outcomes of a statistical experiment
Element | each outcome in a sample space
Event | a subset of a sample space
Complement | the complement of an event A with respect to S is the subset of all the elements of S that are not in A, Or A'
Intersection | The intersection of two events A and B is the event containing all the elements that are common to A and B
Disjoint | if A and B have no elements in common
Union | event containing all the elements that belong to A or B or both
Permutation | an arrangement of all or part of a set of objects
Weights | the likelihood of the occurrence of an event resulting from such a statistical experiment is evaluated by means of a set of real numbers
Conditional probability | the probability of an event B occurring when it is known that some event A has occurred




**Keywords:**

```
chance outcomes, tree diagram, rule method, 
rule of elimination,
```

**Literal Definitions:**

* If an operation can be performed in n1 ways, and if for each of these ways a second operation can be performed in n2 ways, then the two operations can be performed together in n1n2 ways.* If an operation can be performed in n1 ways, and if for each of these a second operation can be performed in n2 ways, and for each of the first two a third operation can be performed in n3 ways, and so forth, then the sequence of k operations can be performed in n1n2 · · · nk ways.

* The probability of an event A is the sum of the weights of all sample points in A

* If an experiment can result in any one of N different equally likely outcomes, and if exactly n of these outcomes correspond to event A, then the probability of event A is P(A) = n/N

* That is, P(B|A) = P(B). When this is true, the events A and B are said to beindependent.

-
### Chapter 3: Random Variables and Probability Distributions
***

**Terms:**

Name  | Description
----- | -----------
Random variable | a function that associates a real number with each element in the sample space
Bernoulli random variable | the random variable for which 0 and 1 are chosen to describe the two possible values
Discrete sample space | a sample space contains a finite number of possibilities or an unending sequence with as many elements as there are whole numbers
Continuous sample space | a sample space contains an infinite number of possibilities equal to the number of points on a line segment
Discrete random variable | its set of possible outcomes is countable
Joint probability distribution | the probability distribution fortheir simultaneous occurrence can be represented by a function with values f(x, y)for any pair of values (x, y) within the range of the random variables X and Y
Statistically independent | f(x,y) = g(x)h(y)



**Keywords:**

```
probability function, cumulative distribution function, 
probability histogram, probability density function, 
cumulative distribution function, joint density function, 
marginal distributions, conditional distributions, 

```

**Literal Definitions:**

* P(a < X ≤ b) = P(a < X < b) + P(X = b) = P(a < X < b). That is, it does not matter whether we include an endpoint of the interval or not.This is not true, though, when X is discrete.

-
### Chapter 4: Mathematical Expectation

***

**Terms:**

Name  | Description
----- | -----------


**Keywords:**

```
mean of the random variable, variance of the random variable,
deviation of an observation
```


**Literal Definitions:**

* Let X and Y be two independent random variables. Then σXY = 0.
* (Chebyshev’s Theorem) The probability that any random variable X will assumea value within k standard deviations of the mean is at least 1 − 1/k*k. That is ``` P(μ − kσ < X < μ+ kσ) ≥ 1 − 1/k*k```

-
### Chapter 5: Some Discrete Probability Distributions

***

**Terms:**

Name  | Description
----- | -----------
Binomial random variable | the number X of successes in n Bernoulli trials
Binomial distribution | the probability distribution of this discrete random variable
Multinomial experiment | each trial have more than two possible outcomes
multinomial distribution | if a given trial can result in any one of k possible outcomes E1,E2,... ,Ek with probabilities p1, p2, . . . , pk, then the multinomial distribution will give the probability that E1 occurs x1 times, E2 occurs x2 times, . . ., and Ek occurs xk times in n independent trials
Hypergeometric random variable | the number X of successes of a hypergeometric experiment
Hypergeometric distribution | the probability distribution of the hypergeometric variable
Negative binomial experiments | instead of the probability of x successes in n trials, where n is fixed, we are now interested in the probability that the kth success occurs on the xth trial
Negative binomial random variable | the number X of trials required to produce k successes in a negative binomial experiment
Poisson experiments | experiments yielding numerical values of a random variable X, the number of outcomes occurring during a given time interval or in a specified region


**Keywords:**

```
Bernoulli process, multinomial experiment, 
geometric distribution, Poisson random variable,
Possion distribution
```


**Literal Definitions:**

* In general, we are interested in the probability of selecting x successes fromthe k items labeled successes and n − x failures from the N − k items labeledfailures when a random sample of size n is selected from N items. This is knownas a ***Hypergeometric experiment***, one that possesses the following two properties:
	* A random sample of size n is selected without replacement from N items.
	* Of the N items, k may be classified as successes and N − k are classified asfailures.
* Properties of the Poisson Process:
	* The number of outcomes occurring in one time interval or specified region ofspace is independent of the number that occur in any other disjoint time intervalor region. In this sense we say that the Poisson process has no memory.
	* The probability that a single outcome will occur during a very short timeinterval or in a small region is proportional to the length of the time intervalor the size of the region and does not depend on the number of outcomesoccurring outside this time interval or region.
	* The probability that more than one outcome will occur in such a short timeinterval or fall in such a small region is negligible.

-
### Chapter 5: Some Continuous Probability Distributions

***


**Terms:**

Name  | Description
----- | -----------
Continuous uniform distribution | this distribution is characterized by a density function that is “flat,” and thus the probability is uniform in a closed interval, say [A, B]

**Keywords:**

```
rectangular distribution, 
```

**Literal Definitions:**