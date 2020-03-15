# Statistics



## **Central Limit Theorem(CLT)**

**> Explanation**
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

Consider we go on deriving the mean of samples for n number of cases, if we plot those means(x̄1,x̄2,.....x̄n) in a separate distribution (which we call as Sampling distribution) then the distribution of the sample means will be approximately normally distributed.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/IllustrationCentralTheorem.png/1920px-IllustrationCentralTheorem.png)

**So What is Central Limit Theorem?**
	    Central Limit Theorem states given a sufficiently large sample size, the sampling distribution of the mean across multiple Samples will approximate a normal distribution. It can also be defined as mean of Sampling distribution of a Sample's mean is almost equal to Population's mean.
		        Sample size(n) should be at least greater than 30 and the number of elements of the sample can be of any size(and should be equal for all samples). As the sample size (n) increases, the standard deviation of the sampling distribution becomes smaller. In other words, the sampling distribution clusters more tightly around the mean as sample size increases.

**Where can Central Limit Theorem be Used?**
       In Statistics, most cases we wont have the actual Population parameters. By using CLT, we can arrive at mean, Standard Deviation of Samples which are also approximately equal to Population's parameters.

## **Confidence Interval & Confidence Level**

**What is Confidence Interval(C.I)?**
    A Confidence Interval is the range of numbers within which our projected data might fall within.

**What is Confidence Level(C.L)?**
   Confidence level is the measure of confidence or level of certainty that our projected data lies within the Confidence Interval.

**Confidence Interval:**
   Confidence Interval can be calculated as 
C.I = μ **_±_** Margin of Error    , where **Margin of Error** is defined as maximum expected difference between the True population parameter and Sample estimate of the parameter. Margin of Error makes sense when always used along side of C.I.

	Margin of Error = Z * Standard Error

**Standard Error(SE)** is similar to Standard Deviation. 
A sample mean deviates from the actual mean of a population—this deviation is the standard error of the mean. It can also be said as Standard Deviation of the Sampling distribution taken from a Population. 

**Pic representing C.I & Confidence Level**
  ![undefined](https://sarathstatsolutions.files.wordpress.com/2020/03/0_pisjcp7tm9oamryg.jpg)

Lets take for example, tomorrow's temperature may vary between 25.5°C- 29.3°C then 25.5°C is the Lower Limit and 29.3°C  is the upper limit.

**Confidence Interval Example**
A Survey was taken in India for how many years a person uses his bike approximately. A random Sample of 52 responses yielded to a mean of 12.4 years. Suppose the Population Standard Deviation for this question is 9.1 years. Using this information construct a 95% Confidence interval for the mean number of years a person would be using a bike in India.

	**Solution:**
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

![Image result for confidence level and z score](https://i.ytimg.com/vi/sJyZ9vRhP7o/maxresdefault.jpg)




## *Z-Score:*

A Z-Score describes how many Standard Deviation a value is from the mean. Z-Score is calculated as below

				z = (X - μ) / σ
where z is the z-score, X is the value of the element, μ is the population mean, and σ is the standard deviation.

In the below diagram, x-axis represents Z-Score

![Image result for z score statistics](https://stats.idre.ucla.edu/wp-content/uploads/2016/02/zdemo1.png)

***Z-Score usually tells us the below***
 a) The probability of a Value occurring in a Normal Distribution
 b) Used in calculating Confidence Interval 

**Z-Score Table:**
A Z-Score table is a table which shows the area or probability of a value to the left of a given Z-score in a Normal Distribution.  

***What are the types of Z-Score Table:***

   There are 2 types of Z-Score Tables
-   Positive Z-Score Table: It means that the observed value is above 0
-   Negative Z-Score Table: It means that the observed value is below 0

**Hypothesis Testing:**
A Hypothesis tests says whether what we found from Inferential Statistics is right or wrong. In other words, the **Hypothesis Testing** is a statistical test used to determine whether the hypothesis assumed for the sample of data stands true for the entire population or not i.e a way for us to test the results of a survey or experiment to see if we have meaningful results.

Two types of Hypothesis

 - Null Hypothesis - Usually represented as Ho is the default or accepted fact
 Example:
    a) Olympics will be conducted as planned
    b) The new Party is no better than the old one
    c) The coin is unbiased
 
 - Alternative Hypothesis - Represented as H1 or Ha contradicts null hypothesis. Usually taken into account when Null Hypothesis is **rejected**

Examples 
  a) Olympics will be cancelled or moved due to Corona outbreak
  b) The new Part is better than the old one
  c) The coin is biased towards head or tails
  
