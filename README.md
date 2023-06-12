# Using-SVM-and-Logistic-Regression
In this project two popular supervised machine learning algorithms SVM and Logistic Regression are used on a dataset and compared.

# Why Logistic Regression was more accurate than SVM?
As seen in the code Logistic regression is significantly more accurate than SVM although usually it is inverse. This is because the dataset is in such a way that it favours logistic regression more than SVM.
The attributes in dataset have almost a linear relation to output. Since Logistic Regression works on y  = 1/1+e^-(b0 + b1x) it handles linear data very well.
Another reason is dataset is comparitively smaller and SVM works much better on bigger datasets.

In practical datasets the relation would not be linear for all attributes and data would be much larger than the one taken for this project. Hence SVM would be a far better algorithm than Logistic Regression.
