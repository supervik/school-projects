# Project: Automatic Review Analyzer

* **Platform**: [edX](https://www.edx.org/)
* **Provider**: [Massachusetts Institute of Technology (MITx)](https://www.edx.org/school/mitx)
* **Course**: [Machine Learning with Python: from Linear Models to Deep Learning](https://www.edx.org/course/machine-learning-with-python-from-linear-models-to)

## About

The goal of this project is to design a classifier to use for sentiment analysis of product reviews.

The training set consists of reviews written by Amazon customers for various food products. The reviews, originally given on a 5 point scale, have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.

Below are two example entries from the dataset. Each entry consists of the review and its label. The two reviews were written by different customers describing their experience with a sugar-free candy.

| Review | label |
|---|:---:|
| Nasty No flavor. The candy is just red, No flavor. Just plan and chewy. I would never buy them again	|−1|
| YUMMY! You would never guess that they're sugar-free and it's so great that you can eat them pretty much guilt free! i was so impressed that i've ordered some for myself (w dark chocolate) to take to the office. These are just EXCELLENT!|1|


In order to automatically analyze reviews and predict the label, the following tasks were completed:

* Implementation and comparison of three types of linear classifiers: the Perceptron algorithm, the Average Perceptron algorithm, and the Pegasos algorithm.
* Verification of classifiers with a sample 2D dataset from toy_data.txt with plotting the resulting model and boundary.
* Implementation the classification accuracy function for measuring the accuracy of the model.
* Implementation of classifiers on the food review dataset, using some simple text features.
* Experiments with additional features to study their impact on classifier performance.
