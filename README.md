# AI-CHATBOT-WITH-NLP

COMPANY: COOTECH IT SOLUTIONS

NANE: sharan ganesh konakala

INTERN ID: CT06DN445

DONAIN: Python Programming

DURATION: 6 WEEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION

The AI Chatbot project is a Python-based application designed to simulate intelligent and friendly conversations with users while answering academic questions. Developed entirely in Visual Studio Code (VS Code), this chatbot provides a simple and interactive interface using Streamlit, a Python library that allows building web apps for data science and machine learning. The core logic of the chatbot is implemented using Natural Language Processing (NLP) techniques powered by NLTK (Natural Language Toolkit), a widely used Python package for text processing tasks. The chatbot uses a rule-based response system combined with keyword matching to handle a variety of userinputs, especially focused on answering questions related to school subjects such as physics, chemistry, biology, and mathematics.

The chatbot has been structured to function without any paid APIs or internet-dependent LLMs, ensuring it is completely offline and free to use. To make the chatbot intelligent enough to understand and respond appropriately, the application makes use of tokenization and keyword identification through NLTK. Basic preprocessing steps such as lowercasing, token splitting, and keyword filtering allow the chatbot to identify the user’s intent and generate responses from a predefined set. A dictionary of intent-response mappings is used for this purpose,covering a wide range of academic topics, along with friendly greetings, farewells, and emotional support phrases to make the interaction more human-like.

During development, several tools and packages were configured. Python 3.13 was installed and configured with system environment variables to ensure command-line tools like streamlit work properly. Streamlit was then used to render the chatbot interface by running the Python script via streamlit run. The Python script was carefully written to handle user input, tokenize it, match it against the known keywords, and return a corresponding response. Special attention was paid to handle edge cases, suchas unknown queries, for which fallback responses were defined to guide users or suggest rephrasing.

The chatbot’s functionality was expanded by manually adding more questions and corresponding answers across subjects. It also includes friendly responses to conversational phrases like "How are you?" or "Tell me a joke." This rule-based approach, while not as flexible as modern AI models like GPT, is highly reliable for fixed domains such as academic support. It also avoids dependency on cloud services or paid API keys, making it suitable for use in offline environments like rural schools or low-resource educational setups.Throughout the setup, several common issues were resolved, such as fixing the PATH variable, downloading missing NLTK resources (like punkt), and organizing Python project files in VS Code. The chatbot code was kept modular and clear, enabling future enhancements, such as integrating a local dataset or expanding to a retrieval-based model using question-answer pairs. In conclusion, this AI Chatbot project demonstrates how to build a friendly and informative assistant for academic purposes using free, open-source tools while maintaining offline capabilities and ease of use through Streamlit in VS Code.

OUTPUT

![Image](https://github.com/user-attachments/assets/1559f039-655e-4ed1-817a-c5cf84d9d764)
