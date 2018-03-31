[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

Code in a Jupyter Notebook may be found at [`../ThinkStats2/code/dsp-questions.ipynb`](../ThinkStats2/code/dsp-questions.ipynb).

```python
from scipy.stats import norm
u = 178
std = 7.7

minimum = (5 * 12 + 10) * 2.54
maximum = (6 * 12 + 1) * 2.54

print(norm.cdf(maximum, loc=u, scale=std) - norm.cdf(minimum, loc=u, scale=std))
```

The estimate provided by the normal distribution indicates that approximately 34.3% of the male population is eligible to join the group based upon height.
