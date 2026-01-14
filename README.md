# final_coursework
The coursework for the class **LELA60331 Computational Linguistics 1**
<br/>
Student: 14332995
<br/>
**Research Objective**
<br/>
The main goal of this experiment is to compare the performance of Logistic Regression and MultiLayer Perceptron in classifying postive and negative sentiment, and investigate and compare the innerworkings of both models. 
<br/>
**Dataset**
<br/>
The dataset used will be from Compiled_Reviews.txt, which is a dataset of customer reviews from Amazon. The size of the data is about 36547 reviews, with a distribution of about 57% positive and 43% negative.
<br/>
**Requirenments to Run the Code**
<br/>
- Python 3.8 or higher
- Numpy
- Scikit-learn
- Matplotlib
<br/>
**Set up instructions**
<br/>
- Setup notebook (.ipynb) environment, and ensure you can run notebook code successfully. If stuck at this, a simple google search should help.
- Most packages should already be installed, if not, use pip to install them
<br/>
**How to Run**
<br/>
- Simply running the notebook from first to last cell should be enough to run the entire codebase.
- However, if you want to analyse the inner workings of the models only, you can start to run the notebook from cell 37. The best models are already selected for you to analyse. 
- You can test out different hyperparameters for the models by invoking the function 
    - MLP_Sigmoid or 
    - logistic_regression_sigmoid
    - Parameters for both are as follows 
    - So far you can only change the n_iters, and lr. 
"""
Accepts 8 parameters
x_dataset and y_dataest used for training 
x_test and y_test used for validation testing 
num_features is the number of features in the dataset
n_iters is the number of iterations
lr is the learning rate
random_seed is the random seed
"""
<br/>
**Interpretable Error Analysis**
<br/>
Explore specific examples where each model succeeds or fails.
- **mlp_wins_indices** - Cases where MLP is correct but Logistic Regression is wrong
- **logreg_wins_indices** - Cases where Logistic Regression is correct but MLP is wrong
- **both_correct_indices** - Cases where both models predict correctly
- **both_wrong_indices** - Cases where both models predict incorrectly
**How to Use**
<br/>
- Run all cells from Cell 37 onwards to generate the error analysis arrays
- The notebook already shows 4 examples from logreg_wins_indices, mlp_wins_indices, and both_wrong_indices.
- To explore other categories, modify Cell 42 by changing logreg_wins_indices[any number you want] or other array you want to explore. 
- Run perform_MLP_analysis or perform_LogReg_analysis to see the analysis with the array entry you want to explore. 
<br/>
 



**Function words list**
<br/>
Function words list: https://www.edu.uwo.ca/about/faculty-profiles/stuart-webb/_docs/essential-word-list.pdf
