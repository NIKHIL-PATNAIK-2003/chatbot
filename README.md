# chatbot
In this Python project with source code, I built a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses.
I used a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then I gave a random response from the list of responses.

# files contents

Intents.json – The data file which has predefined patterns and responses.
train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot.
Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
Classes.pkl – The classes pickle file contains the list of categories.
Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.
Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.

# Here are the 5 steps to create a chatbot in Python from scratch:

Import and load the data file
Preprocess data
Create training and testing data
Build the model
Predict the response
