# [Bayesian Optimization for Hyperparameter Tuning of CNN]

## Description

- **I**: BO-Based CNN focuses on optimizing machine learning when each solution evaluation is costly and/or time-consuming. In particular, current deep learning models, which are complex and computationally intensive, rely on a large number of
hyperparameters that need to be optimized. The purpose is to maximize the performance of these models by optimizing their hyperparameters while saving computational resources.
- **II**: This project is built using [Python, Adaptive Experimentation Platform from facebook, and Pytorch].

**Key Features:**
- **Feature 1**: [AutoML for hyperparameter Tuning]
- **Feature 2**: [Optimizing CNN performance with fewer trials]
- **Feature 3**: [Employing Bayesian optimization to deal with expensive functions]

## Installation

Follow these steps to install and set up the project locally:

1. **Clone the Repository**

   First, clone this repository to your local machine:
   ```bash
   git clone https://github.com/AmgadMonir/BO-Based-CNN.git

2. **Navigate to the Project Directory Change into the project directory**
   ```bash
    cd BO-Based-CNN
   
3. **install Requirement**  You need Python 3.10 or later to run Ax.
    The required Python dependencies are:
     + botorch
     + jinja2
     + pandas
     + scipy
     + sklearn
     + plotly >=2.2.1
     ```bash
     conda install pytorch torchvision -c pytorch  # OSX only (details below)
     pip install 'git+https://github.com/facebook/Ax.git#egg=ax-platform'


checking the Installation of AX framework here
   https://ax.dev/docs/installation.html
