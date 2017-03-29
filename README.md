# KNN-vs-SVM-for-Classification

KNN vs SVM using breast-cancer-wisconsin data.

So which is better ?

KNN has some nice properties: it is automatically non-linear, it can detect linear or non-linear distributed data,
it tends to perform very well with a lot of data points.On the minus side KNN needs to be carefully tuned, the choice of K 
and the metric (distance) to be used are critical. KNN is also very sensitive to bad features (attributes) so 
feature selection is also important. KNN is also sensitive to outliers and removing them before using KNN tends to 
improve results.

SVM can be used in linear or non-linear ways with the use of a Kernel, when you have a limited set of points in many 
dimensions SVM tends to be very good because it should be able to find the linear separation that should exist. 
SVM is good with outliers as it will only use the most relevant points to find a linear separation (support vectors)
SVM needs to be tuned, the cost "C" and the use of a kernel and its parameters are critical hyper-parameters to the algorithm.

So making something useful out of this mess:

- if you have a lot of points in a low dimensional space then KNN is probably a good choice.

- if you have a few points in a high dimensional space then a linear SVM is probably better.

Most likely you will be in the middle of the road and that means that either algorithm can provide the best solution.

For more information https://www.quora.com/What-is-better-K-nearest-neighbor-KNN-or-Support-Vector-Machine-SVM-classifier

https://pythonprogramming.net/

