# Employee Records Search with ChromaDB

This repository contains a Python-based application demonstrating how to manage and search employee records using **ChromaDB**, a popular open-source vector database. This project showcases the power of vector embeddings for semantic search and metadata filtering for structured queries.

## 📊 Project Overview

This lab aims to provide a practical understanding of integrating vector databases into data management solutions. The key objectives achieved are:

* **Collection Creation:** Setting up a dedicated collection in ChromaDB for employee data.
* **Data Storage:** Storing comprehensive employee records, including their unique IDs, detailed text descriptions, and rich metadata.
* **Vector Embedding Generation:** Automatically generating numerical vector representations (embeddings) for employee data using a SentenceTransformer model.
* **Advanced Search Capabilities:** Performing various types of searches on the stored vector embeddings and metadata.

## ✨ Features

The application demonstrates the following search functionalities:

* **Similarity Search:** Find employees whose skills, roles, and experience semantically match a natural language query (e.g., "Python developer with web development experience").
* **Metadata Filtering:** Filter employees based on specific structured criteria from their metadata (e.g., "all Engineering employees," "employees with 10+ years experience," "employees in San Francisco or Los Angeles").
* **Combined Search:** Execute powerful queries that combine both semantic similarity search and metadata filtering for highly precise results (e.g., "senior Python developers in major tech cities with 8+ years experience").

## 🛠️ Technologies Used

* **Python:** The primary programming language.
* **ChromaDB:** The open-source vector database used for storing and querying embeddings and metadata.
* **Sentence-Transformers:** Used as the embedding function (`all-MiniLM-L6-v2`) to convert text into vector embeddings.
* **Google Colab:** The development environment used for running the notebook.

## 🚀 Getting Started

To run this project, you'll need a Google Colab environment or a local Python environment with Jupyter Notebook.

### 1. Install dependencies

Open the `Similarity_Search.ipynb` notebook in Google Colab (or your local Jupyter environment). The first cell in the notebook will handle the installation of necessary Python libraries:

### 2. Run the Notebook

Execute each cell in the `Similarity_Search.ipynb` notebook sequentially. The notebook is structured into logical steps:

* **Step 1-4:** Setup of ChromaDB client, embedding function, and collection.
* **Step 5-7:** Definition and addition of employee data to the collection.
* **Step 8:** Verification of collection contents.
* **Step 9-11:** Implementation and demonstration of advanced search functionalities.

Follow the instructions and output in each cell to see the system in action.

## 📄 License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## ✉️ Contact

For any questions or feedback, feel free to reach out:

* **GitHub:** [AliAbdallah21](https://github.com/AliAbdallah21)
* **Email:** aliabdalla2110@gmail.com
