# Outline

[x] Large Language Model Implementation
    [x] Introduction to LangChain
    [x] Setting API key and .env
    [x] LangChain QuickStart

[x] Build Question-Answering System
    [x] Introduction to Question-Answering System
    [x] Connecting datasource (database and text data) with LLM
    [x] Basics of building Question-Answering System using LLM with database and text data
    [x] Demonstration of using OpenAI and LangChain to build a Question-Answering System
        > Notes: Using Unstructured Text data to answer question from summary text

[x] Hugging Face
    [x] Introduction to Text Generation and Hugging Face
    [x] Setting API key and .env
    [x] Applying HuggingFace's inference API to use LLM without OpenAI credits
        > Notes: Only basic question answering using GPT2 (which is quite lame than openai gpt3)
    [not full] Integrating HuggingFace's Inference API into the previously built Question-Answering System
        > Have tried different model from huggingface to convert natural language to sql but the result not quite right, so I'm not still chaining it up to `SQLDatabaseChain` because it will occur error coz uncorrect sql command.
    [ ] Demonstration of using HuggingFace's Inference API to build a Question-Answering System
        > Haven't use huggingface model to create QnA system from unstructured text data.
    
    Concern:
    - There are quite a lot model we can explore in Hugging Face model, the constrain because lack of experienced to integrate LangChain and HuggingFace. One of the example model is to create QnA system based on given document. [Model](https://huggingface.co/impira/layoutlm-document-qa) I have try it but still got some error.
    - Maybe we can add explanation and review the module to know what should we add afterwards, either example case or code explanation etc.