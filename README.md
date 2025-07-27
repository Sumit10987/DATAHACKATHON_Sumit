**Customer Bot**
This is a Python script that implements a simple customer bot using natural language processing (NLP) techniques. The bot can understand user queries, respond to greetings, and provide information about policies based on user input.

**Features**

Responds to greetings (e.g. "hello", "hi", etc.)
Provides policy information based on user input (e.g. policy ID, vehicle age, model, claim status)
Uses NLP techniques to understand user queries and respond accordingly
Can be trained on a dataset of common responses to improve its accuracy
**How to Use**


Run the script in a Python environment with the required libraries installed (e.g. NLTK, NumPy, Pandas, etc.)
The bot will greet you and ask you to start typing your queries
Type a query or a greeting to interact with the bot
To end the conversation, type "bye"
Code Overview
Importing Libraries
The script starts by importing the required libraries, including NLTK, NumPy, Pandas, and warnings.

**Loading Data**


The script loads a text file containing common responses, which is used to train the bot.

**Preprocessing**


The script preprocesses the data by tokenizing the text into sentences and words, and removing punctuation.

**Defining Functions**

The script defines several functions, including:

*1.check_status*:  retrieves policy information based on a given policy ID

*2.LemTokens*:  lemmatizes tokens using the WordNet lemmatizer

*3.LemNormalize*:  normalizes text by removing punctuation and converting to lowercase

*4.greet*:  responds to greetings

*5.response*:  responds to user queries using cosine similarity and TF-IDF vectorization

**Main Loop**
The script enters a main loop where it waits for user input. If the user types a greeting, it responds accordingly. If the user types a query, it uses the response function to generate a response. If the user types "bye", it ends the conversation.

**Requirements**
Python 3.x
NLTK library
NumPy library
Pandas library
warnings library
License
This script is licensed under the MIT License. See the LICENSE file for details.

**Contributing**
If you'd like to contribute to this project, please fork the repository and submit a pull request.





