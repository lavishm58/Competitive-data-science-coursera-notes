## Week 1

#### Competition Structure
* Data - They have description which is useful for extracting features and analyzing it. In some comp. private data can also be used.
* Model - It can be complex composed of many libraries. It is a method to use data to reach target. It should be accurate on public data and it should be reproducible on unseen data.
* Submission - Sending model to server. Mostly only answers are submitted but in some cases code is also asked to submit.
* Evaluation - It is what which is asked to optimize in comp. It is a f(predicted, correct) -> score
* Leaderboard - before the end of comp. only public data scores are evaluated. Using multiple submission we can get ground truth values of data. After comp ends, model is evaluated on private data which counts for final ranking.

### Recap of ML Models

* Linear(eg logistic regression and svm) - It can be applied on multidimensional data, it data by a line or plane as being above or below it. It is specially good for sparse high d data
     - LOgistic regression use ydash(x) = sigmoid(B0 + B1X), sigmoid(x) = 1/1+e^-x, while linear reg is y(x)=b0+b1X
     - SVM(for both classification and regression) - kernel converts low dim space to high to segregate classes with more accuracy also its prioritie are in this order maximise accuracy>minimise out liers > maximise distance of margin

* Tree based(random forestdecision tree, GBM) - It divides data into two parts by multiple planes, line until maximum accuracy is achieved
### Some good libraries
* Scikit-learn
* Vowpal wabbit - For really large data
