Paste of Piazza 


As we discussed in class, the second coding assignment for you is to implement Huber loss. It would be great if you could submit your completed assignment by Monday. As you know, we will have another assignment coming soon, this time in PyTorch.

 

For the current assignment:

 

(1) Please use the linear model notebook (or your quadratic model notebook) as a starting point.

 

(2) Modify the data generating process by adding extra noise that would generate outliers. In the notebook for in-class instruction I used 4*binomial(1, 0.03, size=n) - 4*binomial(1, 0.03, size=n). Feel free to use any other distribution that generates outliers. (Please keep track of which data points contain this extra noise and which don't.)

 

(3) Instead of mean-squared-error loss, consider Huber loss with a reasonably chosen transition point between the quadratic and the linear part of the Huber loss function.

 

(4) Fit a regression line (or curve) through your data. 

 

(5) Evaluate the mean-squared-error loss for the set of points that were not affected by the extra (outlier-generating) noise.

 

(6) Now evaluate the same (i.e. mean-squared-error loss for the set of points that were not affected by the extra outlier-generating noise) but for a standard regression line (or regression curve). Make sure you use the same data as in part 5.

 

(7) Find out which of these loss values is larger. Did Huber loss improve the result relative to standard regression?

 

Write a short summary of your results (ideally in the PDF format). It would be great if you could then combine your notebooks and the PDF into one zip file and send it to me at fabinger@gmail.com. 

 

Best,

Michal
