# Simulation-Study-on-Sign-Test
We defined thesign Test Statistics.
Keeping the replication number fixed to m=1000, and size n=5,10,...,50, for different parent distribution like standard normal, uniform(-1,1), logistics(0,1),DE(0,1), we simulated the obsrvations and plotted the size vs sample size plot.
Most of the time we see as n is increasing, size tends to 0.05, only exception is shifted exponential(0,1) and uniform(-3,1).
Then we also plotted the power curves of each distribution, and noticed that as sample size is increasing, the power tends to one more rapidly.
We also checked for distribution free nature of sign statistics by the following steps-
Step 1 : We simulate n observations under a continuous distribution F and obtain the value of Sign Statistic.

Step 2: This is repeated m times and Relative Frequency plot is obtained from the data.

Step 3: It is graphically verified that under different underlying null distributions, the density plot does not change its basic nature(size, shape etc.)
Next we checked the asymptotic nature of the sign statistics.
Then we go for size and power comparison for each case through the following steps-
Step 1: We take a CDF F(.) and simulate data . On the same data we employ Sign test and t-test (with the hypotheses as specified earlier) .

   Step 2: From both the tests at level 0.05, size and power are compared by means of suitable graphical method.
Then we go for a real life testing problem based on sign statistics using boostrap method.
