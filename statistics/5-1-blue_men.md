[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

from __future__ import print_function, division

import scipy.stats

#### normal distribution
mu = 178

sigma = 7.7

dist = scipy.stats.norm(loc=mu, scale=sigma)

type(dist)


#### cumulative distributions for the low and high edges of the range.

low = dist.cdf(177.8)    # 5'10"

high = dist.cdf(185.4)   # 6'1"

range_blueman = high-low

print (" The percentage of U.S. male population that can join Blue Man Group is %d%s" % (range_blueman*100,"%"))
