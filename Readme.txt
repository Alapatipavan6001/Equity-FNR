📰 FNR: News Research Tool
FNR (Financial News Research) is a powerful tool that processes and analyzes news articles from specified URLs. It leverages advanced AI models and frameworks such as:

LangChain – For orchestrating and managing the sequence of operations.
OpenAI API – For performing NLP tasks like summarization and answering questions.
Streamlit – For creating an interactive web-based user interface

 #Features

- Fetch and parse news articles from URLs Or parse data from given pdf
- Split articles into manageable chunks
- Create embeddings for the text using OPENAi embedding model
- Store embeddings in a FAISS index for efficient retrieval
- Query the processed data to get answers and sources

#installation:

1. Clone the repository
git clone https://g
github.com/Alapatipavan6001/Equity-FNR.git
 2.install dependencies
!pip install requriments.txt (its for google colab)

3.Run the application using(for google colab to run streamlit app) :
!curl https://loca.lt/mytunnelpassword(It retrieves a secure tunnel URL or token required to establish a connection through localtunnel for accessing the Streamlit application)
!streamlit run FNR.py & npx localtunnel --port 8501( exposes the Streamlit application running on port 8501 to a public URL, allowing you to access the app from any browser)


## Usage:

1.  Open the Streamlit application in your browser.
2.  Select options From dropdown Menu in the sidebar
3.  For URL :
    - Enter the number of URLs you want to process in the sidebar.
    - Provide the URLs for the news articles.
    - Click on "Process URLs" to fetch and analyze the articles.
4.  For pdf
    - Upload a PDF.
    - Click on "process Pdf" to analyze the PDF.
5.  Enter a query in the text input box and click "Submit" to get answers based on the processed data.
Below are the articles links i have used for these project:
https://en.wikipedia.org/wiki/Tesla,_Inc.
https://en.wikipedia.org/wiki/Tata_Group

## Project Structure:

- FNR.py: The main Streamlit application script.
- requirements.txt: A list of required Python packages for the project.
- faiss_store_openai.pkl: A pickle file to store the FAISS index.
- .env: Configuration file for storing your OpenAI API key

