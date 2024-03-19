# Vector Database
# What is a Vector Database
A vector database is a database made to store, manage and search embedding vectors. The use of embeddings to encode unstructured data (text, audio, video and more) as vectors for consumption by machine-learning models has exploded in recent years, due to the increasing effectiveness of AI in solving use cases involving natural language, image recognition and other unstructured forms of data. Vector databases have emerged as an effective solution for enterprises to deliver and scale these use cases.

# Why use a Vector Database
Vector databases enable enterprises to take many of the embeddings use cases we've shared in this repo (question and answering, chatbot and recommendation services, for example), and make use of them in a secure, scalable environment. Many of our customers make embeddings solve their problems at small scale but performance and security hold them back from going into production - we see vector databases as a key component in solving that, and in this guide we'll walk through the basics of embedding text data, storing it in a vector database and using it for semantic search.

Demo Flow
The demo flow is:


# Chroma:
Setup: Here we'll set up the Python client for Chroma. For more details go here
Index Data: We'll create collections with vectors for titles and content
Search Data: We'll run a few searches to confirm it works

# Pinecone
Setup: Here we'll set up the Python client for Pinecone. For more details go here
Index Data: We'll create an index with namespaces for titles and content
Search Data: We'll test out both namespaces with search queries to confirm it works

# Weaviate
Setup: Here we'll set up the Python client for Weaviate. For more details go here
Index Data: We'll create an index with title search vectors in it
Search Data: We'll run a few searches to confirm it works

# Milvus
Setup: Here we'll set up the Python client for Milvus. For more details go here
Index Data We'll create a collection and index it for both titles and content
Search Data: We'll test out both collections with search queries to confirm it works

# Qdrant
Setup: Here we'll set up the Python client for Qdrant. For more details go here
Index Data: We'll create a collection with vectors for titles and content
Search Data: We'll run a few searches to confirm it works

# Redis
Setup: Set up the Redis-Py client. For more details go here
Index Data: Create the search index for vector search and hybrid search (vector + full-text search) on all available fields.
Search Data: Run a few example queries with various goals in mind.

# Typesense
Setup: Set up the Typesense Python client. For more details go here
Index Data: We'll create a collection and index it for both titles and content.
Search Data: Run a few example queries with various goals in mind.
# MyScale
Setup: Set up the MyScale Python client. For more details go here
Index Data: We'll create a table and index it for content.
Search Data: Run a few example queries with various goals in mind.

# Reference Links
1. https://www.nocode.ai/introduction-to-vector-databases/
1. https://github.com/openai/openai-cookbook/blob/main/examples/vector_databases/Using_vector_databases_for_embeddings_search.ipynb
2. https://medium.com/data-engineer-things/why-you-shouldnt-invest-in-vector-databases-c0cd3f59d23c
3. https://github.com/openai/openai-cookbook/tree/main/examples/vector_databases
4. https://www.singlestore.com/spaces/a-deep-dive-into-vector-databases/?category=webinar&utm_medium=email&utm_source=singlestore&utm_campaign=701UJ0000068nT7YAI&campaignid=701UJ0000068nT7YAI
5. https://memsql.wistia.com/medias/wfofsx5ppf?utm_medium=email&utm_source=singlestore&utm_campaign=701UJ0000068nT7YAI&campaignid=701UJ0000068nT7YAI

