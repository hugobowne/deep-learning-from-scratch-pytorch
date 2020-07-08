**After the tutorial, please leave feedback for us [here](https://hugobowne.typeform.com/to/NYClbcaE)! We'll use this information to help improve the content and delivery of the material.**

# deep-learning-from-scratch-pytorch
Deep Learning from Scratch with PyTorch


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hugobowne/deep-learning-from-scratch-pytorch/f61063c3ec3aca124fd90b6af604e8e4c7313604?urlpath=lab)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hugobowne/deep-learning-from-scratch-pytorch/blob/master/notebooks/1-Student-deep-learning-from-scratch-pytorch.ipynb)

# description

This tutorial introduces deep learning (also called neural networks) to intermediate-level Pythonistas. The goal is for participants to develop a sound conceptual foundation for deep learning and to obtain some hands-on experience using an industry-ready toolkit. They will do this in two parts: (1) implementing a neural network classifier from scratch (following a quick review of NumPy array-based computing & supervised learning with Scikit-Learn); and (2) a tour of the PyTorch library building more sophisticated, industry-grade neural networks of varying depth & complexity.



## Prerequisites

Participants will be expected to be comfortable using Python with some prior exposure to NumPy & Scikit-Learn. It would help if you knew

* programming fundamentals and the basics of the Python programming language (e.g., variables, for loops);
* a bit about `pandas` and DataFrames;
* a bit about Jupyter Notebooks;
* your way around the terminal/shell.


**However, we have always found that the most important and beneficial prerequisite is a will to learn new things so if you have this quality, you'll definitely get something out of this tutorial.**

Also, if you'd like to watch and **not** code along, you'll also have a great time and these notebooks will be downloadable afterwards also.

If you are going to code along and use the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3 (see below), we ask that you install it before the session.


## Getting set up computationally

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hugobowne/deep-learning-from-scratch-pytorch/master?urlpath=lab)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hugobowne/deep-learning-from-scratch-pytorch/blob/master/notebooks/1-Instructor-deep-learning-from-scratch-pytorch.ipynb)

The first option is to click on either the [Binder](https://mybinder.readthedocs.io/en/latest/) or [Colab](https://research.google.com/colaboratory/faq.html) badge above. These will spin up the necessary computational environment for you so you can write and execute Python code from the comfort of your browser. They are free services. Due to this, the resources  are not guaranteed, though they usually work well. If you want as close to a guarantee as possible, follow the instructions below to set up your computational environment locally (that is, on your own computer).



### 1. Clone the repository

To get set up for this live coding session, clone this repository. You can do so by executing the following in your terminal:

```
git clone https://github.com/hugobowne/deep-learning-from-scratch-pytorch
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository. If you prefer not to use git or don't have experience with it, this a good option.

### 2. Download Anaconda (if you haven't already)

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3, go get it (n.b., you can also do this w/out Anaconda using `pip` to install the required packages, however Anaconda is great for Data Science and I encourage you to use it).

### 3. Create your conda environment for this session

Navigate to the relevant directory `deep-learning-from-scratch-pytorch` and install required packages in a new conda environment:

```
conda env create -f environment.yml
```

This will create a new environment called deep-learning-from-scratch-pytorch. To activate the environment on OSX/Linux, execute

```
source activate deep-learning-from-scratch-pytorch
```
On Windows, execute

```
activate deep-learning-from-scratch-pytorch
```


### 4. Open your Jupyter notebook

In the terminal, execute `jupyter notebook`.

Then open the notebook `1-deep-learning-from-scratch-pytorch.ipynb` and we're ready to get coding. Enjoy.


### Code
The code in this repository is released under the [MIT license](LICENSE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT). All text remains the Intellectual Property of DataCamp. If you wish to reuse, adapt or remix, get in touch with me at hugo at datacamp com to request permission.
