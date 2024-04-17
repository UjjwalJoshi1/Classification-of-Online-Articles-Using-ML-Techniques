# Classification-of-Online-Articles-Using-ML-Techniques
## Master Project
The project aspires to adeptly classify news articles into predefined categories using machine learning models such as Logistic Regression (LR), Support Vector Machine (SVM), Decision Tree (DT), Random Forest (RF), Gradient Boosting (GB), and Multi-layer Perceptron (MLP) in three different datasets.
### Data Collection: 
The project utilizes a dataset from Kaggle, chosen for its reliability, accessibility, and community validation. The dataset comprises news articles categorized into distinct classes, with each article labeled with a class index, title, and description.
### Data Pre-processing:
Data pre-processing techniques begin with an exploration of the dataset, followed by handling missing data by dropping incomplete rows. Text data in the 'Description' column undergoes thorough text preprocessing like converting text to lowercase, removing non-alphabetic characters, removing stopwords, and stemming using a stemmer object. And Word2Vec technique is used for word embedding.
### Model Selection: 
Explored a variety of machine learning algorithms such as Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, Support Vector Machine, and NN model MLP and all the algorithms undergo hyperparameter tuning using GridsearchCV.
### Model Training and Evaluation:
The test train split technique is used for training the model and testing its performance. This approach helps evaluate how well the model generalizes to new, unseen data. The dataset is randomly divided into three subsets, the training set, Validation set, and the testing set. The model's performance is evaluated by a confusion matrix, classification report, and accuracy score and predictions are calculated on the validation set and testing set.
### Conclusion: 
Despite challenges like class imbalances and model interpretability, Logistic Regression and Multi-Layer Perceptron emerge as strong performers. Both models give good accuracies in three datasets.
