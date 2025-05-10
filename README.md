# approachingML


Testing some machinelearning loosely based on [approachingalmost-repository](https://github.com/abhishekkrthakur/approachingalmost) by Abhishek Thakur [[1]](#1).

## Table of contents

0. Setup

    0. New GitHub-Repository

    1. Create new Virtual Environment
    
    2. Structure project directory

1. Fetch data


## 0. Setup

### 0.0 GitHub-Repository

Create new repository with .gitignore and README.md file.
Edit Markdown file in VS by pressing: ```ctrl + k``` and ```v```.

### 0.1 Virtual Environment

Set up a new Virtual Environment 'env' of a certain python version in /pyver directory:

```
C:/Users/user/pyver/313 -m venv env
```

Activate env with the following terminal command:

```
env/Scripts/activate
```

### 0.2 Project structure

This project uses a directory structure suggested by [Craftwork](https://medium.com/@craftworkai/how-to-structure-a-machine-learning-project-for-optimal-mlops-efficiency-0046e15ce033) [[2]](#2). Exclude certain directories in .gitignore file.

## 1. Fetch data

No machine learning project without data. For example download a dataset from Kaggle like [this](https://www.kaggle.com/datasets/danielpanizzo/wine-quality) one on wine preferences [[3]](#3).

## References

<a id="1">[1]</a> 
A. Thakur (2021). [Approaching (Almost) Any Machine Learning Problem](https://github.com/abhishekkrthakur/approachingalmost).

<a id="2">[2]</a> 
Craftwork (2024).
[How to Structure a Machine Learning Project for Optimal MLOps Efficiency](https://medium.com/@craftworkai/how-to-structure-a-machine-learning-project-for-optimal-mlops-efficiency-0046e15ce033). Medium.

<a id="3">[3]</a> 
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis (2009).
[Modeling wine preferences by data mining from physicochemical properties](http://dx.doi.org/10.1016/j.dss.2009.05.016). 
Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.