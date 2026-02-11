System Architecture



The resume PDF is read and split into text chunks



Each chunk is converted into embeddings using Sentence Transformers



Embeddings are stored in the Endee vector database



User asks a question



The question is converted into an embedding



Endee performs semantic similarity search



Top matching resume chunks are sent to the language model



The model generates a final answer



This pipeline demonstrates Retrieval Augmented Generation (RAG).

