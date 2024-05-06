# PineconeQA
    
- we have a pdf file  
- we load the given document and converts it into chunks (text chunks) because openAI has restrictions related to token size
- then we use openAI embedding which convert it to vector  
- these vectors are stored in vector search db, we will be using Pinecone
- set up a question-answering system that utilizes the OpenAI "gpt-3.5-turbo-instruct" model.


# Prerequisites

- Run pip install -r requirements.txt to install the necessary Python libraries.
- Create a folder named 'documents' to store your PDFs.
- Establish an index within your Pinecone database to accommodate the incoming vector data.
- Integrate calls to the OpenAI and Pinecone APIs within the code wherever necessary.
