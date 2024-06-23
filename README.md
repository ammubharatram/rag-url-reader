# RAG URL Reader Application
This RAG URL Reader is an application designed to load data from URLs and generate answers based on the provided 
context using Large Language Models (LLMs). This application is intended to offer users contextually appropriate 
responses to their inputs, aiding in information retrieval and facilitating smoother interaction within the 
given context. 
 
![RAG URL Reader](images/rag-diagram.png)


# Technology Used
- Python: Programming language used for development.
- Streamlit: Frontend framework for creating interactive web applications.
- Langchain: Utilized for language model integration.
- Google PaLM Embeddings: Transform texts to embeddings.
- Google PaLM and Gemini Pro: Large Language Models used for generating context-based responses.
- FAISS: Vector database for storing and querying embeddings efficiently.


# Features
- Load data from URLs.
- Generate embeddings and store them in a vector database such as FAISS.
- Utilize Large Language Models from Google to generate answers based on the context.
 
# Installation
To install the RAG URL Reader application, follow these steps:

Clone the repository:

    git clone https://github.com/ammubharatram/rag-url-reader.git

Navigate to the project directory:

    cd rag-url-reader

Create and activate virtual environment:

    python -m venv venv
    venv/Scripts/activate

Install the required Python libraries:

    pip install -r requirements.txt

# Usage 

Create a `.env` file using `.env-example` as a template:

    cp .env-example .env

In the `.env` file, insert your [Google API Key](https://aistudio.google.com/app/apikey):

    GOOGLE_API_KEY=your_google_api_key

Run the main application script:

    streamlit run src/app.py

 
# Contribution
Contributions to this project are welcome! Feel free to submit bug reports, feature requests, or pull 
requests to help improve the functionality and usability of the RAG SQL Reader application.

# Disclaimer
This application is intended for educational and informational purposes only. 


# License
This project is licensed under the MIT License. See the LICENSE file for more details.

# Contact
For any questions or suggestions, please reach out to me:

Email: ammubharatram@gmail.com

GitHub username: ammubharatram

[LinkedIn Profile](https://www.linkedin.com/in/bharatramammu/)

