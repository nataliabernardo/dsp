[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d

from __future__ import print_function, division

import numpy as np

import nsfg
import first

preg = nsfg.ReadFemPreg()
live = preg[preg.outcome == 1]


firsts = live[live.birthord == 1]
others = live[live.birthord != 1]

firsts.totalwgt_lb.mean(), others.totalwgt_lb.mean()
diff = firsts.totalwgt_lb.mean() - others.totalwgt_lb.mean()

var1 = firsts.totalwgt_lb.var()
var2 = others.totalwgt_lb.var()
n1, n2 = len(others.totalwgt_lb), len(others.totalwgt_lb)

pooled_var = (n1 * var1 + n2 * var2) / (n1 + n2)
d = diff / np.sqrt(pooled_var)

print (d)
