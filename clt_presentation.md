A practical introduction to the Central Limit Theorem
========================================================
author: Bruno
date: 31/03/2019
autosize: true

The Theorem
========================================================

The Central Limit  is considered one of the most imporant conceps in inferential statistics. It allows the data scientist to make inferences on data whose internal probability distribution is still unknow with easy and robustness.

- Allows inference on any kind of population
- Allows to infer both mean, standard deviation, proportions and differences with the same principle

A Demonstration
========================================================
Consider a random population of numbers. This population is supposed to be the typical distribution of lottery numbers. This population is not normally distributed.

![plot of chunk unnamed-chunk-1](clt_presentation-figure/unnamed-chunk-1-1.png)

True Population Mean: 0.499748

The Problem with samples
========================================================
However, if someone makes a sample from such population the sample has its own distribution. The usual solution to this issue would be to create bigger samples but this costy.

![plot of chunk unnamed-chunk-2](clt_presentation-figure/unnamed-chunk-2-1.png)

Sample Mean: 0.5070708

Inference
========================================================
Thanks to CLT, it is possible to infer the true population mean and other metrics from the samples, since the error for such estimation is normally distributed, no matter the distribution of the population.


```
[1] "Confidence Interval for the Sample:"
```

```
[1] 0.4508719 0.5632697
attr(,"conf.level")
[1] 0.95
```

```
[1] "Means of Means of 100 samples:"
```

```
[1] 0.5075957
```

