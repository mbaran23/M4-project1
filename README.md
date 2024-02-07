# M4-project1
Applied Deep Learning- project 1

Bank Marketing 

After selecting bank marketing data from M1, we imported necessary libraries and loaded the dataset into Python. Subsequently, we performed feature selection by removing less significant columns and engaged in feature engineering. This involved segregating categorical and numerical data, utilizing LabelEncoder to encode categorical features, and scaling the dataset using MinMaxScaler to normalize the numerical features. Furthermore, we addressed the issue of dataset imbalance by employing a random sampler during the data split into test and train sets.

Moving forward, we proceeded to define and train the model using PyTorch, opting for a binary classification model due to the binary nature of the independent variable. ReLU activation function was applied in the input and hidden layers, while the sigmoid function was utilized in the output layer. We conducted five training loops with different hyperparameters.

Despite our efforts, the accuracy achieved in the 5th training loop stood at 0.133. Consequently, there is a recognized need to refine and enhance the model's performance through further adjustments and optimizations.
