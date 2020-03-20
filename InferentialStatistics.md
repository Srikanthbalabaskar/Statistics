Inferential Statistics
In Inferential Statistics, lets talk about Central Limit Theorem, Confidence Interval, Condidence Level and different types of Statistic test used

Central Limit Theorem(CLT)

Explanation
Lets consider an example where our population data is 1,5,8,17,25,35,40
Now let us consider some random samples from our population with a sample length of 4 & derive the means of those

**Population:**
   Values n: 1,5,8,17,25,35,40
Mean μ=(1+5+8+17+25+35+40)/7= 131/7=18.71 
  Stand Deviation S.D= σ/√n

**Samples:**
Case 1 : 
	  Random Samples from Population:1,8,17,25 
      Mean 1 x̄1= (1+8+17/25)/4 = 12.75
Case 2 :
      Random Samples from Population:1,1,35,40
      Mean 2 x̄2= 19.25
 Case 3: 
     Random Samples from Population: 1,5,8,17
     Mean 3 x̄3= 7.75
Consider we go on deriving the mean of samples for n number of cases, if we plot those means(x̄1,x̄2,…x̄n) in a separate distribution (which we call as Sampling distribution) then the distribution of the sample means will be approximately normally distributed.



So What is Central Limit Theorem?
Central Limit Theorem states given a sufficiently large sample size, the sampling distribution of the mean across multiple Samples will approximate a normal distribution. It can also be defined as mean of Sampling distribution of a Sample’s mean is almost equal to Population’s mean.
Sample size(n) should be at least greater than 30 and the number of elements of the sample can be of any size(and should be equal for all samples). As the sample size (n) increases, the standard deviation of the sampling distribution becomes smaller. In other words, the sampling distribution clusters more tightly around the mean as sample size increases.

Where can Central Limit Theorem be Used?
In Statistics, most cases we wont have the actual Population parameters. By using CLT, we can arrive at mean, Standard Deviation of Samples which are also approximately equal to Population’s parameters.

Confidence Interval & Confidence Level
What is Confidence Interval(C.I)?
A Confidence Interval is the range of numbers within which our projected data might fall within.

What is Confidence Level(C.L)?
Confidence level is the measure of confidence or level of certainty that our projected data lies within the Confidence Interval.

Confidence Interval:
Confidence Interval can be calculated as
C.I = μ ± Margin of Error , where Margin of Error is defined as maximum expected difference between the True population parameter and Sample estimate of the parameter. Margin of Error makes sense when always used along side of C.I.

Margin of Error = Z * Standard Error
Standard Error(SE) is similar to Standard Deviation.
A sample mean deviates from the actual mean of a population—this deviation is the standard error of the mean. It can also be said as Standard Deviation of the Sampling distribution taken from a Population.

Pic representing C.I & Confidence Level
undefined

Lets take for example, tomorrow’s temperature may vary between 25.5°C- 29.3°C then 25.5°C is the Lower Limit and 29.3°C is the upper limit.

Confidence Interval Example
A Survey was taken in India for how many years a person uses his bike approximately. A random Sample of 52 responses yielded to a mean of 12.4 years. Suppose the Population Standard Deviation for this question is 9.1 years. Using this information construct a 95% Confidence interval for the mean number of years a person would be using a bike in India.

                 Solution:
n = 52
Sample mean x̄= 12.4
Population Standard Deviation σ = 9.1

C.I = μ **_±_** Margin of Error
M.E= Z*S.E(σ /sqrt n)

In our case, lets take Standard Deviation of 	Sample is same as Standard Deviation of Population. Since we are calculating 95% Confidence Level, refer to Z score(below table) for 95% which 1.96
C.I= 12.4 ± 1.96*(9.1/Sqrt(52))
Since the Sample mean 12.4 years, we get Confidence Interval for 95% as 
C.I= 9.93 < μ < 14.94
So it can be stated that the analyst is 95% confident that in India the actual population mean number of years a person using his bike would be between 9.93 years and 14.94 years.

Image result for confidence level and z score

Z-Score:
A Z-Score describes how many Standard Deviation a value is from the mean. Z-Score is calculated as below

			z = (X - μ) / σ
where z is the z-score, X is the value of the element, μ is the population mean, and σ is the standard deviation.

In the below diagram, x-axis represents Z-Score

Image result for z score statistics

Z-Score usually tells us the below
a) The probability of a Value occurring in a Normal Distribution
b) Used in calculating Confidence Interval

Z-Score Table:
A Z-Score table is a table which shows the area or probability of a value to the left of a given Z-score in a Normal Distribution.

What are the types of Z-Score Table:

There are 2 types of Z-Score Tables

Positive Z-Score Table: It means that the observed value is above 0
Negative Z-Score Table: It means that the observed value is below 0
Hypothesis Testing:
A Hypothesis tests says whether what we found from Inferential Statistics is right or wrong. In other words, the Hypothesis Testing is a statistical test used to determine whether the hypothesis assumed for the sample of data stands true for the entire population or not i.e a way for us to test the results of a survey or experiment to see if we have meaningful results.

There are Two types of Hypothesis

Null Hypothesis - Usually represented as Ho is the default or accepted fact
Examples are
a) Olympics will be conducted as planned
b) The new Party is no better than the old one
c) The coin is unbiased

Alternative Hypothesis - Represented as H1 or Ha contradicts null hypothesis. Usually taken into account when Null Hypothesis is rejected

Examples are
a) Olympics will be cancelled or moved due to Corona outbreak
b) The new Part is better than the old one
c) The coin is biased towards head or tails

Critical Region, One Tailed and Two Tailed Test- Lets find understand what Critical point is.
Critical Point is a value/Point in the test distribution that is compared to the test statistic whether to reject the Null hypothesis.
Whenever we are performing a hypothesis, we need to determine whether we are going to perform a One Tail or Two Tail test. This purely depends on the Alternate Hypothesis H1. In the below diagram, the area in Yellow is called the Tails. The one on the right is called ‘Upper Tail’ or ‘Right Tail’ and the one on left is called ‘Lower Tail’ or ‘Left Tail’.

Image result for critical region and critical value

The area shaded in Blue is the critical region, it is the region of values at which if our test statistic falls then we reject the Null Hypothesis . In other words if our test statistic crosses the Critical Value and falls in Critical Region then we reject Null Hypothesis and accept Alternate Hypothesis. Critical region is also called as Rejection Region.

One Tailed Test
If H1 includes a < sign, then it is lower Tail test
If H1 includes a > sign, then it is Upper Tail test
For Example, if our Null Hypothesis states x<100 and lets consider our Alternate Hypothesis is x>100 then it is one tailed test

Two Tailed Test
If H1 includes a not equal(≠) then we go for a two tailed test
Example is if our Null Hypothesis states that X=100 then our alternate Hypotheses is X≠100 then we need to perform a Two Tailed test

Below is the picture depicting upper one tail and Two tail

Image result for one and two tail in hypothesis

Common Statistics Testing for Inferential Techniques
The common methodologies in Inferential Techniques are Confidence Interval and Hypothesis testing. And the commonly used test statistics are

		 Z test
		 t test
		 χ²(chi-Squared)
		 F test
Z and t test are closely related to the Sampling distribution of the Means while Chi-Squared and F are related to Sampling distribution of Variance

Steps involved in Hypothesis Testing
Below are the 5 steps involved in Hypothesis testing

 State the Null(Ho) and Alternate Hypothesis(H1)
 Choose the Level of Significance(LOS)
 Find Critical Value
 Find Test Statistic(usually from a Sample)
 Draw you conclusion(Reject/Fail to Reject 
  	Null Hypothesis)
We have already seen what is Critical Value. Lets see what is Level Significance(LOS) and Test Statistic are

Level Of Significance - Denoted as α, it is 1- Confidence Level. We usually find the Critical Value based on the LOS.
Example:
Lets take Level of Significance as 5% and find the critical Value. In the below picture, the are in Red is α which is LOS. From LOS, we can calculate the Confidence Level as 95%.

Image result for one tailed test level of significance

From our Z- Score table above, we are able to see that for 95% Confidence Level the Z-Score is 1.96 so our Critical Value is 1.96. If there is no LOS stated then by default we can assume as 5%.

For a 2 Tail test, the LOS is is divided on either side of the graph as α/2. For a 5% LOS, 2.5% rejection region falls on upper tail and 2.5% on lower tail.
Image result for two tailed test LOS
Basically, Level of Significance can be stated a the Probability of rejecting Null Hypothesis when it is True

When to Accept or Fail Null Hypothesis?
Test Statistic is the Value that we find from any of the above 4 mentioned methods(Z,t, Chi-Squared and F Test). From the above 2 tailed test picture, Z=1.25 and it falls within non-rejection region.

test statistic Z(1.25) ≤ Critical Value 		
Z(1.96), so accept Null Hypothesis(Ho)

assume, our test statistic is 2.25 then
test statistic Z(2.25) ≥ Critical Value 		
Z(1.96), so fail to accept Null Hypothesis(Ho)
Z Test
For a Z test to happen, below are the 3 conditions

 Sample size n should be greater than 30
 Population Standard Deviation is known
 Variables should be continuous
Lets take an example

Boys of a certain age are known to have a mean weight of μ = 85 pounds. A complaint is made that the boys living in a municipal children’s home are underfed. As one bit of evidence, n = 32 boys (of the same age) are weighed and found to have a mean weight of ¯x¯ = 80.94 pounds. It is known that the population standard deviation σ is 11.6 pounds. Based on the available data, what should be concluded concerning the complaint?

Step 1- State the Null and Alternate Hypothesis
mean weight of μ = 85 pounds

   Null Hypothesis (Ho ) is μ=85 
   Alternate Hypothesis(H1 or Ha) is μ<85
   Since < is involved it is a One Tailed test
Step 2- Find the Level Of Significance
LOS is not stated in the example above so lets take by default 5% and Confidence Level is 95%

Step 3- Find the Critical Value
From Z table, we are able to find for 95% Confidence interval the z Critical value is -1.645 and the - is because it is a One tailed test & our Alternate Hypothesis involves μ<

Step 4- Find Test Statistic
To find test statistic, the Z formula is given below
**Z Test = (**x̄ – μ) / (σ / √n)

x̄ = 80.94, μ = 85, σ=11.6 and n=35
So, Z=(80.94-85)/(11.6/√35) which gives Z= -2.07

Step 5- Draw your Conclusion
Our test statistic Z test -2.07 < z critical Value -1.645 i.e our test statistic crosses the critical Value and falls under Rejection region so we reject Null Hypothesis

Conclusion/Interpretation - Boys living in a municipal children’s home are underfed

T Test or Student ‘t’ Test

For a T test to happen, below are the 3 conditions

 Sample size n should be less than 30
 Population Standard Deviation is not known
 Variables should be continuous
Do note that the above first 2 conditions are just opposite of Z Test i.e in a Z test Sample Size is greater than 30 and Population S.D is known. What if our Sample size is greater than 30 and Population S.D is not know? Yes, we can go for T Test as the S.D is not know

t statistic or t score= (**x̄ – μ) / (**s/ √n),
where s is the Sample Standard Deviation

Confidence Interval to estimate Population Mean
Since in a T Test, Population S.D is not know, we will not be able to find Population Mean. In order to find atleast the range in which it falls, we go for Confidence Interval

x̄-tn-1, α/2 s√n ≤ μ ≤ x̄+tn-1, α/2 s√n

Where,
x̄ is the Sample mean, s is the Sample S.D, n is the Size of the sample, n-1 is the degree of freedom and α is the area in the tail of distribution. Since we are dealing with Confidence Interval and the graph is Symmetrically distributed between 2 tails, each tail contribute to α/2

Degrees of Freedom refers to the maximum number of logically independent values, which are values that have the freedom to vary, in the data sample. When estimating the mean or proportion from a single sample, the Number of independent observations is equal to n-1.

Example:
A Manufacturing company manufacture screws with average diameter of 100 mm. As per quality control specification, 10 screws are sampled.
An analyst wants to estimate the interval for the true mean of the batch with 95% confidence and assume the data is normally distributed

Data are as follows
98.6 102.1 100.7 102.0 97.0 103.4 98.9 101.6
102.9 105.2

Mean x̄ = 101.24
n=10
n-1(Degrees of Freedom) = 9
S.D s= 2.48
Confidence Level =95% which means α=0.05 and α/2=0.025

In a T table, the X-axis is α value and Y-axis is Degrees of Freedom. So from the below table , t9,0.025 =2.262
Image result for t table value

Confidence Interval Formula is
x̄-tn-1, α/2 s√n ≤ μ ≤ x̄+tn-1, α/2 s√n

101.24-2.2622.48/√10 ≤ μ ≤101.24+2.2622.48/√10
99.47≤ μ ≤103.01
The Analyst would be confident that the average screw size would range between 99.47 mm and 103.01 mm

Chi-Squared( χ2) Test

Chi-Squared test is used to find variance of a Single Population Variance.
The formula for calculating Chi-Squared Statistic is

		χ2=(n−1)s²/σ²
Where df(n-1) is the degree of Freedom,
s is the Sample Standard Deviation
σ is the Population S.D

The above is similar to how we calculate Sample Variance
s²=∑(xi−¯x)²/n−1

Testing Hypothesis about a Variance

A manufacturing company produces bearings of 2.65 cm in diameter. A major customer requires that the variance in diameter be no more than 0.001 cm2. The manufacturer tests 20 bearings using a precise instrument and gets the below values. Assuming the diameters are normally distributed, can the population of these bearings be rejected due to high variance at 1% significance level.

Below are the give data
2.69, 2.66, 2.64, 2.59, 2.62, 2.63, 2.69, 2.66, 2.63, 2.65, 2.57, 2.63, 2.70, 2.71, 2.64, 2.65, 2.59, 2.66, 2.62, 2.57

sample size n=20
population variance=σ2=0.001
level of significance α=1% or 0.01
Degree of freedom =n−1 which is 20−1 =19

Here we are talking about only 1 Population So we are going for Chi-Squared Test

Lets perform our steps for Hypothesis

Step 1: State Null and Alternate Hypothesis
the variance in diameter be no more than 0.001 cm2
Null Hypothesis (Ho ) diameter ≤ 0.001
Alternate Hypothesis(H1 or Ha) diameter > 0.001
Since > is involved it is a One Tailed test i.e right Tailed
Step 2: Find the LOS
Level of significance α=0.01
Step 3: Find the Critical Value:
Similar to T test, Chi-Squared table also has X-axis as Level of Significance and Y-Axis as Degrees of Freedom

If we see the below table, X-axis 0.01 and Y-axis 19 meet at value 36.191

Image result for chi-square test table 19 degrees of freedom

Step 4: Find the Test Statistic
Below is the formula for finding test statistic
χ2=(n−1)s²/σ²
χ2=(19*0.001621)/ 0.001
χ2=30.8
We can find Variance s² using Online Variance calculator or in excel using the formula VAR.S(Sample Variance, S denotes Sample)
Step 5: Draw your Conclusion
Test Statistic (χ2) 30.8< Critical Value 36.191 i.e test Statistic did not cross the critical Value So we Accept Null Hypothesis
To conclude the variance in diameter is not more than 0.001 cm2

F Test:
We are aware that ChiSquared(χ2) is used to Testing Hypothesis of a Single Population Variance. For testing Hypothesis of two Different Population, we go for F Test.
Example:
Do Biscuits manufactured in 2 different Shift or two different Production Units or 2 different batches have the same variance or not

F= S1²/ S2²=est.σ1²/est.σ1²

Where S1 is the standard deviation of sample 1 and S2 is the standard deviation of sample 2. It is basically ratio between Variance of Two different Samples. Also it can put as Ratio of 2 Chi-Squares, each divided by its degree of Freedom

F test is used mainly on the below

if the 2 samples come from the same population
or the 2 samples come from a different population with the same variance
F Distribution - Since F test deals with 2 different Samples,
there are two Degrees of Freedom involved for each sample. Also for both Chi-Squared and F Test, the distribution is Skewed to the right
Image result for f distribution

Hypothesis Test of 2 Sample Variances( Application of F Test)
A machine produces metal sheets with 22mm thickness. There is a variability in thickness due to machines, operators, manufacturing environment, raw material, etc. The company wants to know the consistency of two machines and randomly samples 10 sheets from machine 1 and 12 sheets from machine 2. Thickness measurements are taken. Assume sheet thickness is normally distributed in the population.

The company wants to know if the variance for each sample comes from the same population variance (i.e. population variances are equal) or from different population variances (population variances are unequal).

Machine 1
|22.3|21.8|22.3|21.6|21.8|21.9|22.4|22.5|22.2|21.6|

Machine 2
|22.0|22.1|21.8|21.9|22.2|22.0|21.7|21.9|22.0|22.1|
21.9|22.2

Variance of machine 1 σ1² =0.11378 & n1=10
Variance of machine 2 σ2² =0.02023 & n2=12

Please note that the sample size in population need not be equal when performing F Test

Lets as usual go step by step for our hypothesis test
Step 1: State the Null & Alternate Hypothesis
Refer to the below statement from our given problem statement
The company wants to know if the variance for each sample comes from the same population variance (i.e. population variances are equal) or from different population variances (population variances are unequal).

So the null Hypothesis (Ho ) is Variance 1(σ1²)= Variance 2(σ2²)
Alternate Hypothesis Variance 1 ≠Variance 2
Since a ≠ is involved in Alternate Hypothesis, it is 2 Tailed Test

Step 2: Find the L.O.S
Since L.O.S is not given by default it is 5% Significance so
α=5% or 0.05. And since it is a 2 tailed-test, α/2=0.025 for each tail

Step 3: Find the Critical Value
The degrees of Freedom df1=9(10-1) and df2=11
Unlike the Chi-Squared, the F Table has Degrees of Freedom on both the axis. Lets take the table for α=0.025 , X-axis value=9 & Y-axis value=11 and the
F0.025,9,11=3.5879
F0.975,9,11=1/3.5879=0.2787

Image result for f table statistics 0.025

Note that there are multiple F tables for different α values

Step 4: Find Statistic Value
We know that Ratio F=Variance of machine 1 / Variance of machine 2
F=0.11378 /0.02023 =5.62 which is our critical Value

Step 5: Provide your Conclusion
Our test statistic 5.62 is greater than the Critical Value 3.5879 so we fail to accept the Null Hypothesis.

It can also be started as the variance in Machine 1 and Machine 2 are not equal. Machine 1 has a higher variance and hence needs to be inspected for issues.

Below is the picture depicting rejection region
Image result for f table rejection
