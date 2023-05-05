Download Link: https://assignmentchef.com/product/solved-cuny605-assignment16
<br>
Your final is due by the end of the last week of class.  You should post your solutions to your GitHub account or RPubs.  You are also expected to make a short presentation via YouTube  and post that recording to the board.  This project will show off your ability to understand the elements of the class.

<strong>Problem 1.</strong>

Using R, generate a random variable X that has 10,000 random uniform numbers from 1 to N, where N can be any number of your choosing greater than or equal to 6.  Then generate a random variable Y that has 10,000 random <em>normal </em>numbers with a mean of m=s=(N+1)/2.

<em>Probability.   </em>Calculate as a minimum the below probabilities a through c.  Assume the small letter “x” is estimated as the median of the X variable, and the small letter “y” is estimated as the 1st quartile of the Y variable.  Interpret the meaning of all probabilities.

<em>5 points</em>           a.   P(X&gt;x | X&gt;y)                    b.  P(X&gt;x, Y&gt;y)                   c.  P(X&lt;x | X&gt;y)

<em>5 points.  </em> Investigate whether P(X&gt;x and Y&gt;y)=P(X&gt;x)P(Y&gt;y) by building a table and evaluating the marginal and joint probabilities.

<em>5 points.  </em>Check to see if independence holds by using Fisher’s Exact Test and the Chi Square Test.  What is the difference between the two? Which is most appropriate?

<strong>Problem 2</strong>

You are to register for Kaggle.com (free) and compete in the House Prices: Advanced Regression Techniques competition.  <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques">https://www.kaggle.com/c/house-prices-advanced-regression-techniques</a> .  I want you to do the following.

<em>5 points.  Descriptive and Inferential Statistics. </em>Provide univariate descriptive statistics and appropriate plots for the training data set.  Provide a scatterplot matrix for at least two of the independent variables and the dependent variable. Derive a correlation matrix for <em>any </em>three quantitative variables in the dataset.  Test the hypotheses that the correlations between each pairwise set of variables is 0 and provide an 80% confidence interval.  Discuss the meaning of your analysis.  Would you be worried about familywise error? Why or why not?

<em>5 points. Linear Algebra and Correlation.  </em>Invert your correlation matrix from above. (This is known as the precision matrix and contains variance inflation factors on the diagonal.) Multiply the correlation matrix by the precision matrix, and then multiply the precision matrix by the correlation matrix. Conduct LU decomposition on the matrix.

<em>5 points.  Calculus-Based Probability &amp; Statistics</em>.  Many times, it makes sense to fit a closed form distribution to data.  Select a variable in the Kaggle.com training dataset that is skewed to the right, shift it so that the minimum value is absolutely above zero if necessary.  Then load the MASS package and run fitdistr to fit an exponential probability density function.  (See  <a href="https://stat.ethz.ch/R-manual/R-devel/library/MASS/html/fitdistr.html">https://stat.ethz.ch/R-manual/R-devel/library/MASS/html/fitdistr.html</a> ).  Find the optimal value of l for this distribution, and then take 1000 samples from this exponential distribution using this value (e.g., rexp(1000, l)).  Plot a histogram and compare it with a histogram of your original variable.   Using the exponential pdf, find the 5<sup>th</sup> and 95<sup>th</sup> percentiles using the cumulative distribution function (CDF).   Also generate a 95% confidence interval from the empirical data, assuming normality.  Finally, provide the empirical 5<sup>th</sup> percentile and 95<sup>th</sup> percentile of the data.  Discuss.

<em>10 points.  Modeling</em>.  Build some type of <em>multiple </em>regression  model and <strong>submit your model</strong> to the competition board.  Provide your complete model summary and results with analysis.  <strong>Report your Kaggle.com user name and score.</strong>