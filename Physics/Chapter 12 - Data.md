## Measures of central tendency
- What is mean?
	- sum of all things divided by number of things

- What is median?
	- The middle value in a set of things if you have odd num things. The average of 2 middle things if you ahve even num things.

- How does having an outlier v large affect the mean?
	- Skews it up

- How does having an outlier v small affect the mean?
	- Skews it down


- If mean and median are far from each other what does that mean?
	- That there's an outlier


- What is the mode?
	- The data point that appears most common


## Distributions
- What is a normal distribution?
	- A distribution of some statistic that peaks in the middle and goes down symmetrically towards the ends.

- What are the characteristics of a standard distribution?
	- Mean of 0
	- Standard deviation of 1


- What is a skewed distribution?
	- A distribution that is skewed one way or another in how it looks

- What is a negatively skewed distribution?
	- Visual shift is opposite to the direction of skew

- What is a negatively skewed distribution?
	- Shift towards the higher end

- What is a positively skewed distribution?
	- Shift towards the smaller end

- What is a bimodal distribution?
	- Has 2 peaks instead of 1, with a valley in the middle

- How many modes in a bimodal distribution?
	- Can have 1 mode or 2 modes

- Do bimodal distributions have to be analyzed as 2 separate distributions?
	- No.


## Measures of Distribution
- What is the range of a dataset?
	- The max value - min value

- Is range heavily or loosely affected by outliers?
	- Heavily (eg 2 outliers on either end would widen the range even if all the data is in the middle)

- What are quartiles?
	- Divide data into groups that comprise 1/4 of the entire set.

- What is the most appropriate way to calculate quartiles?
	- Sort the data in ascending order
	- For Q1 take the number of datapoints n and do n/4
	- If n/4 is is whole number then 1st quartile is mean of the n/4th value and n/4 + 1 value
	- If n/4 is a decimal then quartile is position is at the value of rounded up position
	- To get Q3 take n and multiply it by 3/4. If whole number then mean of that value + next position. If decimal then round up and use that value
	- IQR = Q3 - Q1


- How do you determine outliers using interquartile ranges?
	- Any number that is Q1 - 1.5IQR or Q3 + 1.5IQR is an outlier

- How do you calculate standard deviation?
	- For every data point, do sum ((x-mean)^{2} / (num data points - 1))


- What is an outlier relative to standard deviation?
	- Any number that is +/- 3 standard deviations from the mean is an outlier

- What are the 3 causes of outliers?
	- statistical anomaly
	- measurement error
	- a skewed distribution

## Probabilty
- What are independent events?
	- Events that have no impact on each other
	- Roll a die and get a 3, and then roll a die and get a 6. Both rolls are independent of each other.
- WHat are dependent events?
	- Events that do depend on each other.
	- From a bag of 6 balls, 3 blue and 3 orange 1/2 orange, 1/2 blue, pick 1 orange. Then have 3 blue and 2 orange.
	- Probability of orange now is 2/5 orange, 3/5 blue

- What is a mutually exclusive event?
	- Events that cannot occur at the same time.
	- Eg cannot flip heads and tails in one go

- What is an exhaustive set?
	  An exhaustive set of outcomes overs the entire set of what can happen.


- For independent events, what is probablilty of both events happening?
	- P(A and B) = P(A) x P(B) = P(A \union B)


- For independent events what is probability of atleast 1 event occuring?
	- P(A or B) = P(A) + P(B) - P(A and B)


: In a certain population, 10% of the population has diabetes and 30% is obese. If 7% of the population has both diabetes and obesity, 
	are these events independent? 
	If one chose an individual at random from this population, 
	what would be the probability of that patient having at least one of the two conditions?

- P(D) = 10% has diabetes
- P(D x O) = 7% both diabetes and obese
- P(O) = 30% has both diabetes and obese

- P(D or O) = P(D) + P(O) - P(O and D)
	P(D or O) = 0.1 + .3 - .07
		        = .4 - 0.07
		        = 0.33


## Statistical Testing
- What is the null hypothesis?
	- Hypothesis that there isn't any statisitcally significant diffference between the control and treatment groups

- What is the alternative hypothesis?
	- Opposite to null hypothesis

- What is a z/t test
	- Rely on a standard distribution or a t-distrubtion

- How is z/t test used?
	- 1. compute a statistic for the sample
	- 2.calculate a p-value for the sample
		- Get a likelihood that the statistic is obtained via random chance assuming null hypothesis is strue
	- 3. Calculate a significance value (a)
		- If p-valeu is greater then (a) we fail to reject null hypothesis, meaning that not a statisitically significant difference between populations
		- If p < a then we reject null hypothesis and say that there is a statistically signifcant differecne between groups
	- Test statistic is calculated and compared to a table to determine the likelihood that the statistic was obtained via random chance

- What does the value of a represent?
	- The level of risk that we are willing to accept for incorrectly rejecting the null hypothesis. 


- What is a type I error?
	- When we report a difference between populations that does not exist 
	- When we 

- What is a type II error?
	- We do not report a difference between populations that does exist

- What is probabilty of type II error labelled as
	- $\beta$ 

- What is power? 
	- Rejecting a null hypothesis that is false
	
- What is power labelled as?
	- $1-\beta$

- What is confidence?
	- Probability of failing to reject a true null hypothesis (reporting no difference when a difference does not exist)


- Turn into cloze deletion
	- ![[Pasted image 20250506114712.png]]

- What is a confidence interval?
	- Determine the range of values from sample mean and standard deviation
	- Begin with a desired confidence level (.95) and use a table to find t/z score
	- Multiple z/t score by standard deviation and +/- from the mean we create a range of values


- Eg we want to consider a population to know what the mean age is, at 95% confidence.
	- We get a sample from the population and get a mean of 30, with standard deviation of 3
	- The z score is 1.96 at .95 confidence
	- The range is then 30-3(1.96) and 30+3(1.96)
	- 24.12 to 35.88
	- We are 95% confident that true mean age is 24.12 and 35.88

## Charts and Graphs
- When is a pie chart used?
	- To represent relative amounts of entities

- What is downside of pie chart?
	- As num categories increases, visual representation of pie loses impact 

- What are pie charts used to show usually?
	- Demographic info

- What is a bar chart?
	- Categories on one side and the size of the bar is the numerical information about the categories

- What is a histogram?
	- Particularly useful at determining the mode of a dataset

- What is a box plot?
	- Show range, median, quartiles and outliers![[Pasted image 20250506115601.png]]

	- ![[Pasted image 20250506115706.png]]
		- Where is Q1?
			- Bottom line
			- 
		- Where is Q3?
			- Top line
		
		- What is median?
			- The line through the box
		
		- What is the horizontal lines on top and bottom?
			- The max and min

		- What is the graph?

- What is a semi log graph?
	- x axis contains regular intervals
	- y axis contains log scale (10, 100,1000)

- What is a log/log graph?
	- Both x and y axis are plotted using logs

- How to read a log axis?
	- The marks between points are spaced equally in value
	- ![[Pasted image 20250506120455.png]]
- What is correlation?
	- When independent variable and dependent variable seem to be related, they trend together


- What is a correlation coefficient?
	- Degree to which correlation is happening. -1 to 1. If 1 then dep increases as x increases. -1 then dep decreases as y increases. 

- Does correlation imply causation?
	- No.