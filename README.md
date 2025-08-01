# Sequential Minimal Optimization (SMO) for Hard Margin SVM Classification
This project implements the Sequential Minimal Optimization (SMO) algorithm to train a Support Vector Machine (SVM) classifier using hard margin classification. The classifier is evaluated on linearly separable data using two kernel functions:
 - LinearKernel: K1(x,y)=x⋅y
 - QuadraticKernel: K2(x,y)=[K1(x,y)+1]^2
