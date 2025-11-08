# Chroma-DB-and-embeddings

## Overview
A simple project demonstrating how to use Chroma DB with Python for similarity search using embeddings.

## How It Works
- Connects to Chroma DB and sets up SentenceTransformers for text embeddings.
- Creates a sample collection of grocery-related text data.
- Performs a similarity search using a query term like “apple” and returns the top similar items.

## Conclusion
In this project, I worked with Chroma DB to understand how it can be used for similarity search and text embeddings. 
I started by connecting Python with Chroma DB, setting up a client, and configuring embeddings using SentenceTransformers.

For data handling, I created a collection called **"my_grocery_collection"** where I added some sample text documents related to grocery items. 
Each document had its own ID and metadata. When the data was added, the embedding function automatically generated vector representations for those texts.

Finally, I built a function called **perform_similarity_search** to test how the similarity search works. 
I used the query term “apple” and the function returned the top three most similar text documents from the collection, 
showing how Chroma DB finds related information based on embeddings.
