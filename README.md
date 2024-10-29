📚 Inverted Index Search System


Project Description

This project implements an Inverted Index Search System that allows users to search for documents based on their content. The system creates an inverted index from a collection of documents, enabling efficient search and retrieval of relevant documents based on user queries.

Key Features

📄 Document Indexing: Automatically processes and indexes a collection of documents to create an inverted index.
🔍 Query Search: Allows users to enter a query and retrieve a list of matching document IDs.
🌐 Tokenization and Preprocessing: Utilizes tokenization, stemming, and lemmatization to improve search accuracy.
🚫 Stop Words Removal: Excludes common stop words from the indexing process to focus on meaningful terms.
⚡ Efficient Search Mechanism: Quickly finds documents that match the query using the built inverted index.


Technologies Used

Python – Programming language used for implementation.
NLTK – Natural Language Toolkit for text processing and analysis.
Regular Expressions – For text cleaning and tokenization.
Data Structures – Utilizes dictionaries and lists for efficient data storage and retrieval.

Getting Started

To run the project locally, follow these steps:

Clone the Repository:

bash

git clone https://github.com/your-username/inverted-index.git
cd inverted-index
Install NLTK:
Make sure you have the necessary libraries installed:

bash

pip install nltk
Download NLTK Resources:
Uncomment the following lines in your code to download the required NLTK resources (if not already done):

python

# nltk.download('stopwords')
# nltk.download('wordnet')
Run the Program:
Execute the main script to build the inverted index and start searching:

bash

python main.py
Enter a Query:
When prompted, enter your search query to find matching documents.

Code Structure
bash

inverted-index/
│
├── main.py             # Main script to run the program
├── inv_index.py        # Module containing the InvIndex class
└── README.md           # Project documentation
Contributing
Contributions are welcome! Feel free to submit a Pull Request with improvements or enhancements.
If you encounter any issues, please open an Issue in the repository.
License
This project is licensed under the MIT License.

Acknowledgements
Thanks to everyone who contributed to this project! Happy searching! 🕵️‍♂️

