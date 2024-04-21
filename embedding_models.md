# Vector_database
# Different embedding models
1. all-mpnet-base-v2
```
from sentence_transformers import SentenceTransformer
embedding_model = SentenceTransformer(model_name_or_path="all-mpnet-base-v2",
                                      device="cpu")
https://github.com/mrdbourke/simple-local-rag/blob/main/video_notebooks/00-simple-local-rag-video.ipynb
```
2. text-embedding-ada-002 : open AI 
3. Cohere Embedding models
4. AWS Embedding models
5. hugging face embedded models 
