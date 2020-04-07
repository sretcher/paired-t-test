
#### Comparing Two Population Means: Paired Difference Experiments
To combat red-light-running crashes, many states are installing red light cameras at dangerous intersections. The Virginia Department of Transportation conducted a study in Fairfax County, Virginia to see if photo-red enforcement programs are effective in reducing red-light-running crashes at intersections. The study provides crash data (measured as the number of crashes caused by red light running per intersection per year) before and after installing red light cameras at 13 randomly selected intersections.

We will use a one sample t-test on the sample of differences to see if the true mean number of crashes at at intersections with installed cameras is less than the true mean number of crashes at intersections without cameras. 

#### Assumptions Required for Valid Small-Sample Inferences about ud

1. The data must be paired.

2. A random sample of differences is selected from the target population of differences.

3. The population of differences has a distribution that is approximately normal.

Looking at the information provided, our data is paired since crash data was recorded twice at each intersection. Consequently, making a column of differences between crash data for each intersection can be regarded as a random sample of crash data differences for all intersections in Fairfax County, Virginia. Looking at a normal probability plot, we see that our data is a little off from being normal, but since t-test are robust against departures in normality, we will consider this and all assumptions to be fulfilled.

#### Paired Difference Test of Hypothesis for ud = (u1 - u2)

First, we make a column of crash data differences (after cameras - before cameras). We will use our random sample of differences to make inferences about the mean of the population of differences, ud, which is equal to u1 - u2. u1 = the true mean number of crashes at at intersections with installed cameras in Fairfax County, Virginia and u2 = the true mean number of crashes at intersections without cameras in Fairfax County, Virginia. We are interested in whether red light cameras decrease the average amount of red-light-running crashes.

Ho: ud = 0

Ha: ud < 0 


#### Small Sample Student's t-Test Statistic





