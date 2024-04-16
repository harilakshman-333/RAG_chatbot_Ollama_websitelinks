# RAG_chatbot_Ollama_websitelinks

1. Install Ollama (to run LLM models locally)

Download Ollama & run the open-source LLM
First, follow these instructions to set up and run a local Ollama instance:\
   a. Download and install Ollama onto the available supported platforms (including Windows Subsystem for Linux)\
   b. Download the model you want to use Ollama run mistral\
   c. Fetch available LLM model via ollama pull mistral

3. #pip install streamlit langchain_community
(We'll import the required modules from Streamlit and LangChain community libraries. Streamlit is used for creating the web app interface, while LangChain provides tools for text splitting, embeddings, vector storage, and retrieval-based question answering.)

4. #streamlit run <filename.py> 
if above command does not work try 

   #python -m streamlit run <filename.py>
