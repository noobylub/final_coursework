# final_coursework

The coursework for the class **LELA60331 Computational Linguistics 1**

Student: 14332995

## Research Objective

The main goal of this experiment is to compare the performance of Logistic Regression and MultiLayer Perceptron in classifying postive and negative sentiment, and investigate and compare the innerworkings of both models.

## Dataset

The dataset used will be from Compiled_Reviews.txt, which is a dataset of customer reviews from Amazon. The size of the data is about 36547 reviews, with a distribution of about 57% positive and 43% negative.

## Requirenments to Run the Code

- Python 3.8 or higher
- Numpy
- Scikit-learn
- Matplotlib

## Set up instructions

- Setup notebook (.ipynb) environment, and ensure you can run notebook code successfully. If stuck at this, a simple google search should help.
- Most packages should already be installed, if not, use pip to install them

## How to Run

- Simply running the notebook from first to last cell should be enough to run the entire codebase.
- However, if you want to analyse the inner workings of the models only, you can start to run the notebook from cell 37. The best models are already selected for you to analyse. 
- You can test out different hyperparameters for the models by invoking the function 
    - MLP_Sigmoid or 
    - logistic_regression_sigmoid
    - Parameters for both are as follows 
    - So far you can only change the n_iters, and lr. 


## Interpretable Error Analysis

Explore specific examples where each model succeeds or fails.

- **mlp_wins_indices** - Cases where MLP is correct but Logistic Regression is wrong
- **logreg_wins_indices** - Cases where Logistic Regression is correct but MLP is wrong
- **both_correct_indices** - Cases where both models predict correctly
- **both_wrong_indices** - Cases where both models predict incorrectly

### How to Use

- Run all cells from Cell 37 onwards to generate the error analysis arrays
- The notebook already shows 4 examples from logreg_wins_indices, mlp_wins_indices, and both_wrong_indices.
- To explore other categories, modify Cell 42 by changing logreg_wins_indices[any number you want] or other array you want to explore and assign this to variable, index_to_analyse for example 
- Run perform_MLP_analysis or perform_LogReg_analysis with index_to_analyse as the parameter to see the analysis inner workings of the model.

## Function words list

Function words list: https://www.edu.uwo.ca/about/faculty-profiles/stuart-webb/_docs/essential-word-list.pdf
