# Spam Detector

## About
This program is developed to demonstrate my learnings as a part of AI Boot-camp by University of Pennsylvania, Liberal and Professional Studies. [More Info...](https://bootcamp.sas.upenn.edu/artificial-intelligence/landing/)
<br/><br/>
This program puts the topics discussed in **Classification in Machine Learning** into action

## Topics covered in this program
1. **Splitting Data**:
    - Checking data distribution by `value_counts()` on target column
    - Splitting datasets using `train_test_split()` function

2. **Scaling Data**:
    - Identifying scale differences by observing dataframe
    - Using `StandardScaler` to scale features data

3. **Using Logistic Regression Model**:
    - Creating model using `LogisticRegression` class
    - Fitting training data using `fit()` method
    - Predicting test values using `predict()` method
    - Calculating socres using `score()` and `accuracy_score()` functions 
4. **Using Random Forest Classifier**:
    - Creating model using `RandomForestClassifier` class
    - Fitting training data using `fit()` method
    - Predicting test values using `predict()` method
    - Calculating socres using `score()` and `accuracy_score()` functions
5. **Analyzing Model Performances**:
    - Reviewing and comparing **training accuracy**
    - Reviewing and comparing **testing accuracy**
    - Indentifying **Bias** and **Variance**
    - Interpreting scores



## How to run this program
Follow instructions below to run this program
> NOTE: Following setup and commands are tested in macOS Sonoma 14.5 only

### Pre-requisites
- **Anaconda** (recommended for environment management)
- **Homebrew** (for installing dependencies)
- Python 3.x
- Pandas library
- SKLearn library

Install Anaconda and set up your environment:

```bash
# Install Anaconda using Homebrew
brew install --cask anaconda

# Create a new environment (optional but recommended)
conda create -n dev python=3.10

# Activate the environment
conda activate dev

# Install necessary libraries
conda install pandas
conda install scikit-learn
```
## Usage
- Checkout git repository using git clone
`git clone https://github.com/36kp/classification-challenge.git`
- Go to the repo home directory
`cd \YOUR_PATH\classification-challenge`
- Execute the Jupyter Notebook
`jupyter notebook`
- Open `spam_detector.ipynb` from browser