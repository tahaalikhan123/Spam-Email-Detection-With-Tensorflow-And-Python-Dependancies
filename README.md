# Spam-Email-Detection-With-Tensorflow
develop a machine learning model for the detection of spam emails using the TensorFlow framework. Spam email detection is a common application of natural language processing and machine learning, where the goal is to classify emails into spam and non-spam categories.

#Data Loading and Exploration:
Loaded the dataset from a CSV file containing email messages and their corresponding labels (spam or non-spam).
Explored the dataset to understand its structure and characteristics.

#Data Preprocessing:
Split the dataset into training and testing sets to evaluate the model's performance.
Tokenized the email messages and padded the sequences to prepare the data for input into the neural network model.

#Model Building:
Constructed a simple neural network model using the Sequential API from TensorFlow.
Utilized dense layers with a rectified linear unit (ReLU) activation function in the hidden layer and a sigmoid activation function in the output layer for binary classification.

#Model Compilation:
Compiled the model using the Adam optimizer and binary cross-entropy loss function, suitable for binary classification tasks.
Set accuracy as a metric to monitor during training.

#Model Training:
Trained the model on the training data for a specified number of epochs and batch size.
Monitored the training process to detect any potential issues or improvements.

#Model Evaluation:
Evaluated the trained model on the testing data to assess its generalization performance.
Obtained metrics such as test loss and accuracy to quantify the model's effectiveness.

#Making Predictions:
Used the trained model to make predictions on new email messages.
Interpreted the model's predictions in terms of predicted probabilities for spam classification.
Visualization:

Created visualizations to enhance understanding and interpretation of the model's behavior.
Plotted training and validation loss over epochs to monitor training progress.
Generated a confusion matrix to assess the model's performance in terms of true positives, true negatives, false positives, and false negatives.
Plotted an ROC curve to visualize the trade-off between sensitivity and specificity.

The Jupyter notebook is attached, play around with it and would love your inputs :)

<<<<Basic steps to follow and if you are new to Python and its dependancies>>>>

                                 <<<<For Windows>>>>
Install Python 3 or higher version by visiting the official python website : https://www.python.org/downloads/

Install jupyter :
Open CMD or any CLI of your preference
Type in:
pip install jupyter
Press enter....

Download the dataset from kaggle
Link here : https://www.kaggle.com/datasets/mfaisalqureshi/spam-email

Create a folder or on your desktop or working directory, navigate to the directory using:
CD
In the CMD type:
jupyter notebook
Press enter....   this will open a jupyter notebook in your default browser

                                <<<<For macOS>>>>
Refer to online guides, not a mac user so my badddddd 
xD
Probably chatgpt or some other AI tool might help you out...


