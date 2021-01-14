#### Statistical Inference Quiz 1:
*Author: Alexander M Fisher*

**********

##### Question 1:

Consider influenza epidemics for two parent heterosexual families. Suppose that the probability is 17% that at least one of the parents has contracted the disease. The probability that the father has contracted influenza is 12% while the probability that both the mother and father have contracted the disease is 6%. What is the probability that the mother has contracted influenza?

###### Answer:

11%

**********

##### Question 2:

A random variable, XX is uniform, a box from 0 to 1 of height 1. (So that its density is f(x) = 1f(x)=1 for 0\leq x \leq 10≤x≤1.) What is its 75th percentile?

###### Answer:

0.75

**********

##### Question 3:

You are playing a game with a friend where you flip a coin and if it comes up heads you give her XX dollars and if it comes up tails she gives you YY dollars. The probability that the coin is heads is pp (some number between 00 and 11.) What has to be true about XX and YY to make so that both of your expected total earnings is 00. The game would then be called “fair”.

###### Answer:

p/1-p = Y/X

**********

##### Question 4:

A density that looks like a normal density (but may or may not be exactly normal) is exactly symmetric about zero. (Symmetric means if you flip it around zero it looks the same.) What is its median?

###### Answer:

The median is at 0.

**********

##### Question 5:

Consider the following PMF shown below in R

```r
x <- 1:4
p <- x/sum(x)
temp <- rbind(x, p)
rownames(temp) <- c("X", "Prob")
temp
```

```r
## [,1] [,2] [,3] [,4]
## X 1.0 2.0 3.0 4.0
## Prob 0.1 0.2 0.3 0.4
```

What is the mean?

###### Answer:

3

**********

##### Question 6:

A web site [(www.medicine.ox.ac.uk/bandolier/band64/b64-7.html)](www.medicine.ox.ac.uk/bandolier/band64/b64-7.html) for home pregnancy tests cites the following: “When the subjects using the test were women who collected and tested their own samples, the overall sensitivity was 75%. Specificity was also low, in the range 52% to 75%.” Assume the lower value for the specificity. Suppose a subject has a positive test and that 30% of women taking pregnancy tests are actually pregnant. What number is closest to the probability of pregnancy given the positive test?

(Hints, watch Lecture 3 at around 7 minutes for a similar example. Also, there's a lot of Bayes' rule problems and descriptions out there, for example here's one for HIV testing. Note, discussions of Bayes' rule can get pretty heady. So if it's new to you, stick to basic treatments of the problem. Also see Chapter 3 Question 5.)

###### Answer:

40%

**********