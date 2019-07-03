# Project description
_ First udacity project regarding to find the Donors for charityML. 
With nearly 15 million working Californians, CharityML has brought us on board to help build an algorithm to best identify potential donors and reduce overhead cost of sending mail. 

Our goal will be to evaluate and optimize several different supervised learning algorithms to determine which algorithm will provide the highest donation yield, while also reducing the total number of letters being sent.

# project sketch
 * explore the data to learn how the census data is recorded
 * apply a series of transformations and preprocessing techniques 
 * evaluate several supervised learners of choice on the data
 * optimize the selected model and present it as the solution to CharityML
 * tests performance on  given data

# implementing
* load data from U.S. census
* Choose measure metrics is fbeta score and accuracy, beta as 0.5.
* transformd numeric data with  log scaler,minmax scaler, categorrical data is one hot encoded.
* compare SVM,NB,Adaboost classifer on training and testing data
* Apply gird search on Winner algorithm
* Test on tuned algorithm ,Adaboost, elicit accuracy of 86.51% 

# Software and libraries
1 Python 3.7
2 NumPy
3 pandas
4 scikit-learn (v1.17)
5 matplotlib

