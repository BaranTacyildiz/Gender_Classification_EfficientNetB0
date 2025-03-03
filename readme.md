# Gender Classification with EfficientNETB0 

## How to install dataset

import kagglehub

path = kagglehub.dataset_download("cashutosh/gender-classification-dataset")
print("Path to dataset files:", path)


## How to file directories must be designed

./Project_Folder/
                 ./Training/
                 ./Validation/
                 ./main.ipynb


## About the model

I used EfficientNETB0 CNN algorithm to classify gender.
Batch Size = (32)
Input Shape = (64x64x3)
Optimizer = Adam
Loss Function = Sparse Categorical Entropy

## Evaluation of model on the test dataset

        precision    recall  f1-score  
female     0.98      0.95      0.96      
male       0.95      0.98      0.96             

    