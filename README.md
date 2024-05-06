# PineconeQA

project workflow:
    
- we have a pdf/book/document of any sort 
    
- we load the given document and converts it into chunks (text chunks) because openAI has restrictions related to token size

- then we use openAI embedding which convert it to vector
    
- these vectors are stored in vector search db, we will be using Pinecone

- set up a question-answering system that utilizes the OpenAI "gpt-3.5-turbo-instruct" model.
