[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> REPLACE THIS TEXT WITH YOUR RESPONSE

n = np.random.random(1000)

pmf = thinkstats2.Pmf(n)
thinkplot.Pmf(pmf, linewidth=0.1)
thinkplot.Config(xlabel='Random variate', ylabel='PMF')

cdf = thinkstats2.Cdf(n)
thinkplot.Cdf(cdf)
thinkplot.Config(xlabel='Random variate', ylabel='CDF')
