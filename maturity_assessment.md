For any 3rd Party Foundation Model Endpoint usage, it's possible to look up:
- Which endpoint & version is used.
- The structure of request & response.
- Token usage cost.
- Latency.
- Prompts that are sent to the endpoint and response.

For embeddings creation (for vector database), it's possible to look up:
- Computational latency (for computing embeddings).
- Latency (for endpoint if used to get embeddings).
- How documents are parsed.
- How chunks are created (the size).
- What model is used to generate the embeddings.

For storing embeddings in a vector database, it is possible to lookup:
- How the database is updated with new documents.
- The metadata saved with chunks.
- Which document and part of the document a chunk is from.

For retrieving embeddings from the vector database, it is possible to lookup:
- How many chunks are retrieved.
- The strategy for combining chunks.
- The strategy for integrating retrieved chunks into the prompt.
- The relevancy ranking.
- Metadata filtering.
- Which metadata is retrieved with embeddings.
- Which similarity algorithm is used.

For any prompt [prompt engineering], it's possible to lookup:
- How the user query is enriched before it is sent to the foundation model [structure].
- How external context is integrated into the user query (for RAG case).

For fine-tuned model deployment, it’s possible to look up:
- Corresponding code commit on Git.
- Infrastructure used for fine-tuning & serving.
- What model artifact is produced.
- What training data is used.
- Retraining strategy is clearly defined, including how often.
- Methodology is defined (supervised, self-supervised, RLHF).
