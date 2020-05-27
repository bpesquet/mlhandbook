![Supported Python Versions](https://img.shields.io/badge/Python->=3.6-blue.svg?logo=python&logoColor=white)

# Machine Learning Handbook

This repository contains theorical explanations and interactive demonstrations for various Machine Learning concepts, techniques and tools. Practical challenges can be found in the associated [Machine Learning Katas](https://github.com/bpesquet/machine-learning-katas) repository.

The interactive demos use [Jupyter](https://jupyter.org/) notebooks that can be executed either:

- locally, by cloning or downloading this repository then spinning up a Jupyter notebook server on your local machine.
- online, through [Colaboratory](https://colab.research.google.com/) (Google account needed). To do so, open any notebook and click this button: ![Open In Google Colaboratory](https://colab.research.google.com/assets/colab-badge.svg).

> This material is part of the Machine Learning course taught at [ENSC](https://ensc.bordeaux-inp.fr). [ENSEIRB-MATMECA](https://enseirb-matmeca.bordeaux-inp.fr) and [IOGS](https://www.institutoptique.fr).

## Workflow

- [Machine Learning In Action](notebooks/workflow/ml_in_action.ipynb)
- [Machine Learning Fundamentals](notebooks/workflow/ml_fundamentals.ipynb)

## Tools

- [Python](notebooks/tools/python.ipynb)
- [NumPy](notebooks/tools/numpy.ipynb)
- [pandas](notebooks/tools/pandas.ipynb)
- [Matplotlib/Seaborn](notebooks/tools/matplotlib.ipynb)
- [scikit-learn](notebooks/tools/scikit-learn.ipynb)
- PyTorch [ [Overview](https://www.bpesquet.fr/en/slides/ai/pytorch/) | [Demo](notebooks/tools/pytorch.ipynb) ]

## Models

### Machine Learning

- K-Nearest Neighbors [ [Overview](https://www.bpesquet.fr/en/slides/ai/k-nearest-neighbors/) | [Demo](notebooks/models/knn.ipynb) ]
- Linear Regression [ [Overview](https://www.bpesquet.fr/en/slides/ai/linear-regression/) | [Demo](https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=25&networkShape=&seed=0.27079&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=regression&initZero=false&hideText=false&showTestData_hide=false&activation_hide=true&noise_hide=false&discretize_hide=true&dataset_hide=true&batchSize_hide=true&percTrainData_hide=true&numHiddenLayers_hide=true&problem_hide=true) ]
- Logistic Regression [ [Overview](https://www.bpesquet.fr/en/slides/ai/logistic-regression/) [Demo](https://playground.tensorflow.org/#activation=sigmoid&batchSize=10&dataset=gauss&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=&seed=0.61489&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false&numHiddenLayers_hide=true&percTrainData_hide=true&discretize_hide=true&problem_hide=true&activation_hide=true) ]
- Ensemble Methods [ [Overview](https://www.bpesquet.fr/en/slides/ai/ensemble-methods/) | [Demo](notebooks/models/decision_trees.ipynb) ]

### Deep Learning

- [Neural Networks](notebooks/models/neural_networks.ipynb)
- [Convolutional Neural Networks](notebooks/models/cnn.ipynb)
- Generative Adversarial Networks [ [Overview](https://www.bpesquet.fr/en/slides/ai/generative-deep-learning/) ]
