## LangChain Chat with Your Data

![image](https://github.com/imkushwaha/LangChain_Chat_with_Your_Data/assets/72372136/a29c95ee-ba3d-40e9-aeb2-eaa922173c3a)


- A short course by DeepLearning.AI


### Create a virtual environment
```python
py -3 -m venv <environment name>
```

### Activate the virtual environment
```bash
venv\Scripts\activate.bat
```

### Install all dependencies using requirements.txt
```python
pip install -r requirements.txt
```

#### Different componets:

- **Document Loading**: How to use LangChain to load data from a variety of documents sources using LangChain's 80-plus different document loaders.
- **Document Splitting**: After loading the documents, we split the documents into chunks and talk about a lot of the nuances that arrive when doing so.
- **Vectorstores and Embedding**: After that, we take those chunks, create embeddings for them, and put them into a vector store, showing how that easily enables semantic search. Also talk about some of the downsides of semantic search and where it can fail on the certain edge cases that arise.
- **Retrieval**: Here we talk about a lot of new and advanced and really fun retrieval algorithms for overcoming those edge cases.
- **Question Answering**: We take those retrieved documents, we take the user question, we pass it to an LLM, and we generate an answer to the original question.
- **Chat**: Creating a fully functioning end-end chatbot over our data.
