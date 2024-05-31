# Traffic-bot: Traffic Law Conversational AI

## Overview

Traffic-bot is a project aimed at implementing an efficient conversational AI system for traffic-related inquiries on a website. It provides information about traffic rules, regulations, punishments, fines, and challans. This README provides an overview of the project methodology, components, challenges, and future improvements.

## Methodology

The project leverages retrieval augmented generation (RAG) techniques with a large language model (LLM) to handle traffic-related queries. The methodology can be broken down into the following key steps:

1. **Data Collection and Preprocessing**:
   - Gather information from official traffic regulation documents, websites, and legal acts.
   - Preprocess the collected data to extract relevant information and remove unnecessary content.

2. **Text Embedding and Database Creation**:
   - Utilize a suitable text embedding model to convert preprocessed text segments into vector embeddings.
   - Create a database of vector embeddings using efficient indexing techniques for fast similarity search.

3. **Retrieval QA Chain**:
   - Construct a retrieval QA chain integrating the language model with the vector database retriever.
   - Process user queries, retrieve relevant documents from the vector database, and generate coherent responses based on the retrieved context.

## Challenges

The project encountered several challenges during development:

- **Data Collection and Storage**: Gathering and organizing information from various sources into a structured format for easy retrieval.

- **Selection of Embedding Model**: Choosing an appropriate embedding model to represent traffic-related text accurately while balancing computational efficiency.

## Future Improvements

Potential enhancements for Traffic-bot include:

- Implementation of automated data scraping and updating mechanisms to ensure the database is up-to-date with the latest traffic regulations.
  
- Experimentation with different language models or fine-tuning existing models to improve response accuracy.
  
- Optimization of system architecture for scalability and reduced computational overhead.

## Results

### Results obtained from the model:

[Sample Result Image](link_to_image)

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your_username/traffic-bot.git

1. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt

1. **Create Embeddings:**

   ```bash
   python ingest.py

1. **Run the application:**

   ```bash
   python app.py
