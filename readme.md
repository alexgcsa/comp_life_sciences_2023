# Machine Learning - Computing for Life Sciences 2023 

by [@alexgcsa](https://twitter.com/alexgcsa)


## Main Colab Notebook
The main material can be accessed via Google Colab Notebook:
- [Introduction to Support Vector Classifier (SVC)](https://colab.research.google.com/github/alexgcsa/comp_life_sciences_2023/blob/master/Intro_to_SVC.ipynb)
- [ML on PPI Small Molecules Inhibitors (Classification)](https://colab.research.google.com/github/alexgcsa/comp_life_sciences_2023/blob/master/lecture1_classification.ipynb)
- [ML on PPI Small Molecules Inhibitors (Regression)](https://colab.research.google.com/github/alexgcsa/comp_life_sciences_2023/blob/master/lecture2_regression.ipynb)



## Extra Colab Notebooks

The extra material can be accessed via Google Colab Notebooks:
- [Iris Classification Colab](https://colab.research.google.com/github/alexgcsa/comp_life_sciences_2023/blob/master/iris.ipynb)
- [Disease Classification Colab - Part 1](https://colab.research.google.com/github/alexgcsa/comp_life_sciences_2023/blob/master/mlw_disease_class_p1.ipynb)
- [Disease Classification Colab - Part 2](https://colab.research.google.com/github/alexgcsa/comp_life_sciences_2023/blob/master/mlw_disease_class_p2.ipynb)


## Local installation

Alternatively, if you want to run it locally, we suggest you use [Anaconda](https://docs.anaconda.com/free/anaconda/install/) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)) to manage a virtual environment and install dependencies.


### First, create an environment with the following command:

```bash
$ conda create -n wml
```

### Then, install dependencies via pip:


```bash
$ conda activate wml

$ conda install python=3.10

$ pip install -r requirements.txt
```

### If you need to run under this environment at any time, use the following commands to activate it and open the notebook:

```bash
$ conda activate wml

$ jupyter lab
```
**OR**
```bash
$ conda activate wml

$ jupyter lab --ip=127.0.0.1 --port=8888
```


