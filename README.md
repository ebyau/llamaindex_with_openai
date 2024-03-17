# llamaindex_with_openai
A Retrieval Augmented Generation (RAG) Application using `llamaindex` and `openai`.  
The RAG Application can take questions and return answers based on the 2 papers.  
The PDFs used are 2 papers i.e. [Attention](https://arxiv.org/abs/1706.03762) and [YOLO](https://arxiv.org/abs/1506.02640).  
You need to have an API Key from OpenAI. To learn where your openai key [HERE](https://help.openai.com/en/articles/4936850-where-do-i-find-my-openai-api-key).  
Llamaindex is used to index the PDFs and convert them to embeddings.  
When the number of PDFs grows very large, it is better to store the index embedding on a hard disk than in memory.

1. Obtain openai key
2. Create a `.env` file and store your openai key. ``openai_api_key  = xxxxxx``
3. create a virtual environment. ``conda create -n rag-apps python=3.10 -y``
4. clone the repository
5. Run ``pip install -r requirements.txt``
6. Create folder titled `data` where you will place your PDFs
7. Run the cells in Notebook.
