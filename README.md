# Closed-Domain RAG Model for Question Answering

# Overview
This project aims to create a closed-domain Retrieval-Augmented Generation (RAG) model capable of reading the content of various files and accessing this information to function as a question and answer system.

# Technologies Used
Python: The primary programming language used for developing the project.
ElasticSearch: Used for indexing and searching the content of files.
BM25 Retriever: A retrieval component for identifying relevant documents.
Haystack: Provides functionalities such as FARMReader and ExtractiveQAPipeline.
Pre-trained model: Utilizes roberta-base-squad2 for question answering tasks.

# Prerequisites
Before running the project, ensure you have the following:

Python installed on your system.
Access to ElasticSearch, BM25 Retriever, and Haystack libraries.
Installation
Clone this repository to your local machine.
bash
Copy code
git clone https://github.com/renatovillela93/RAG_OpenAI.git
Install the required Python packages.
bash
Copy code
pip install -r requirements.txt

# Usage
Run the necessary services such as ElasticSearch, BM25 Retriever, and Haystack.
Execute the main script to start the question answering system.

# Contribution
Contributions to this project are welcome! If you'd like to contribute, feel free to fork the repository and submit a pull request with your changes.

# Future Improvements
One of the next steps for this project is to enhance the quality of answers by fine-tuning the model to improve information retrieval.

# Get in Touch
If you have any questions, suggestions, or just want to chat about the project, feel free to reach out!
 
