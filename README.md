# Stat tests

## Purpose
To gain a better understanding of statistical tests and when/how to apply them in python for EDA purposes.

My source is from [Machine Learning Mastery](https://machinelearningmastery.com/statistical-hypothesis-tests-in-python-cheat-sheet/). This talks about various tests, but not all.

The other [source](https://machinelearningmastery.com/a-gentle-introduction-to-normality-tests-in-python/) is also from Machine Learning Mastery and relates more to normality tests.

## Conclusions
Normality:
- Hard Fail:
    - Use non-parametric tests
    - Explore transformation to make data more normal like
    - consider relevence of feature too
    - Failure of one test = non-normal
- Soft Fail:
    - Some tests indicate normal or normal like others are not
    - Treat data like normal and perform parametric tests.