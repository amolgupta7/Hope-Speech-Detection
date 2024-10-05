# Hope-Speech-Detection

Hope is considered significant for the well-being, recuperation and restoration of human
life by health professionals. Psychologists, sociologists and social workers in the
Association of Hope have concluded that hope can also be a useful tool for saving people
from suicide or harming themselves.
Hope speech reflects the belief that one can discover pathways to their desired objectives
and become roused to utilize those pathways. I performed an experiment on Hope Speech
dataset for Equality, Diversity and Inclusion.
------------------------------------------------------------------------------------------------------------------------------------------------------------------
The Project work conducted on the Hope speech EDI datasets. The dataset provide by Hope Speech EDI is based on YouTube comments, it consists of 22740 comments as train set, 2841 as validation set, 2843 as test set. Train and val. Set are labeled set and test sets are unlabeled.
------------------------------------------------------------------------------------------------------------------------------------------------------------------
The model used in this Proposed work is Roberta-base from RobertaForSequenceClassification [12] class which inherits from pretrained models of transformers. This model consists of 12 layers, a hidden size of 768, with 12 attention head and 50265-word embeddings. Further, the activation function used in the model is GELUActivation.
------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Results

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 0.86     | 0.68      | 0.81   | 0.72     |
| SVC                 | 0.87     | 0.68      | 0.75   | 0.70     |
| BERT                | 0.90     | 0.89      | 0.91   | 0.89     |
| RoBERTa             | 0.94     | 0.93      | 0.94   | 0.93     |
