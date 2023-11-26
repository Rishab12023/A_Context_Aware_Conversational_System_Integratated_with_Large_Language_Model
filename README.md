## Overview

This repository contains a conversational retrieval system implemented using the LangChain framework. The system integrates a Language Model (LLM), a vector store, and a memory mechanism to provide contextual answers to user queries.

## Features

- **Language Model (LLM):** The system uses GooglePalm as the language model, providing powerful language understanding capabilities.

- **Vector Store:** Qdrant is employed as the vector store for efficient storage and retrieval of document vectors.

- **Memory Mechanism:** The ConversationBufferMemory stores and retrieves conversation history, enabling the system to maintain context during interactions.

- **Web API with Flask:** The implementation includes a Flask web application that exposes an API endpoint (`/ask`) for users to submit queries and receive contextual responses.

## Setup

1. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Run the main file:

    ```bash
    python main.py
    ```
3. Run the test file:
   
    ```bash
    python test.py
    ```

    The application will run on `http://localhost:5000`.
# Sample Queries
======================================================================================================================================================================
=== Welcome to the Conversational Retrieval System ===
This script interacts with a Flask API for contextual answers.
Enter your query, and the system will provide a response.

Query:
----------------
Enter your query: give me product description about garlic oil

System Response:
-----------------
Response: This Product contains Garlic Oil that is known to help proper digestion, maintain proper cholesterol levels, support cardiovascular and also build immunity.
Query:
----------------
Enter your query: Suggest some good hair products

System Response:
-----------------
Response: Biotin & Collagen Volumizing Hair Shampoo + Biotin & Collagen Hair Conditioner, Argan-Liquid Gold Hair Spa, Cold Pressed Bhringraj Cooling Oil For Hair Fall & Damage Control
Query:
-----------------
Enter your query: what is ginger oil

System Response:
-----------------
Response: ginger oil is an essential oil that is extracted from the ginger root. It has a strong, pungent aroma and is used in a variety of applications, including aromatherapy, cooking, and medicine.
======================================================================================================================================================================
