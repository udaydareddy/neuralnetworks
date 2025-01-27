***Customer Churn Prediction Through ANN***
 Summary
This project features a complete deep learning pipeline which incorporates an artificial neural network for customer churn prediction. The implementation is completed through python with Keras and TensorFlow. The project dataset is, Churn_Modelling.csv.
This project comprises the following functions:
 **Data Preprocessing:** All preprocessing steps were automated in a single function such as:
 ~Categorical variables encoding
 ~Numerical features and other features scaling
 ~Splitting of the entire dataset into training and validation sets
**Model Development:**
 Sequential model with 100 nodes in 2 hidden layers Sequential model with 100 nodes in 2 hidden layers
Training models:
 ~Adam optimizer used
 ~Activation functions used are ReLU and sigmoid
 ~Binary cross-entropy loss
 **Model Training and Evaluation:**
 The model was evaluated based on a batch size of 32, epochs of 100 and training accuracy displayed per epoch.

 ***Dataset***
 The `Churn_Modelling.csv` file in the root directory of the project.
 ***Procedure***
 1. Library Importation
  Import  libraries used in this, they are: tensorflow, Pandas, Numpy, Scikit-learn, etc,.

 2. Data Preprocessing
  **Categorical Encoding:**
    The "Geography" and "Gender" columns are encoded using "LabelEncoder" and "OneHotEncoder" respectively.
  **Feature Scaling:**
    StandardScaler is used to normalise the data.

 3. ANN Architecture
   **Input Layer:** 12 features after preprocessing
   **Hidden Layers:** Two dense layers with ReLU activation
   **Output Layer:** One node with Sigmoid activation for binary classification

 4. Model Compilation and Training
  **Optimizer: Adam
  **Loss Function: Binary Crossentropy
  **Metrics: Accuracy
  **Epochs: 100

 5. Model Performance
During training, the results are printed at each epoch










