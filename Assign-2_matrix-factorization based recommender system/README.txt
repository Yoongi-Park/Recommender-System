1:- How to:
	compile  & Run: python Assign2_1.py training_filename testing_filename Parameter_filename

It takes 3 arguments all of them are filenames.

Parameter_file format:
	first line: list of K values separated by space.
	second line: list of Lemda values separated by space.
	third line: list of maximumIteration values separated by space.
	fourth line: list of Epsilon values separated by space.

example:
	for parameters given in Assignment text.
/file starts
10 50
0.01 0.1 1.0 10
50 100 200
0.0001 0.001 0.01
/file ends
same sample is attached in Assignment submission.

Bonus file works similarly with command = python Assign2_1Bonus training.txt testing.txt parameter.txt


Note:

For given training and testing set results for configuration given by Prof. is as below:

K = 20, Lemda = 3, maxIter = 100 & Epsilon = 0.00001

Assign2_1.py  gives: 		MSE =  1.06425138
Assign2_1Bonus.py gives:	MSE =  1.00334203


For Bonus Question:

I have implemented similar approach with separate User Bias & Item Bias. Used combination of both biases with general mean with 0.5 weightage to get better results.
