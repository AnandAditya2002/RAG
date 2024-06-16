
# RAG-Retrieval Augmented Generation

Retrieval-Augmented Generation (RAG) is an AI technique that combines retrieving relevant information from a large dataset and using a text generation model to produce accurate and contextually relevant responses. This approach enhances the quality of generated text by leveraging a wide array of sources and sophisticated language models, making it useful for tasks like question answering and summarization.


## 🚀Table of Contents 

- Overview
- Features
- Installation
- Usage
- Screenshots
- Results and Metrics
- Contributing
- License
- Contact



## 📖Overview
 RAG(Retrieval Augmented Generation) is a project that implements a chatting interface
 capable of answering questions based on a **Restaurant's Q/A PDF**, **Parivahan's O/A PDF**, **Election Commision's Q/A PDF**. It utilizes LangFlow to
 integrate Azure OpenAI embeddings and handles keys and tokens, while AstraDB is used for
 storing vectorized words and sentences.

## 📖Features
- **ChatInterface:** Interactive chat interface to answer queries based on the FAQ PDF.
- **Integration with Azure OpenAI:**  Uses Azure OpenAI embeddings for accurate answer retrieval.
- **Vector Storage:** AstraDB is used to store vectorized representations of words and sentences.
- **EnhancedRetrieval:**  Combines retrieval and generation for accurate and relevant answers.

##  🧵Installation
To get started with this project, follow the steps below:

- **Prerequisites**
    - Python 3.7+
    - AzureOpenAI API key
    - AstraDB credentials
    - Necessary Python libraries (listed in requirements.txt)
- **Steps**
     1. **Clone the Repository**
         - bash
         - Copy code : git clone https://github.com/taakasj/RAG.git cd RAG
     2. **Install Dependencies**
         -  bash
         - Copy code :  pip install-r requirements.txt
     3. **Set Up Environment Variables**
         -  Create a .env file in the root directory and add your Azure OpenAI API key and AstraDB credentials.
         -  bash
         -  Copy code :
            - AZURE_OPENAI_API_KEY=your_api_key
            - ASTRA_DB_API_KEY=your_astra_db_api_key
            - ASTRA_DB_ENDPOINT=your_astra_db_endpoint
            - ASTRA_DB_APPLICATION_TOKEN=your_astra_db_application_token
     4. **Run the Application**
           - bash
           - Copy code : python app.py  

## 🔰Usage
 After installation, run the application as described above. Open your browser and navigate to
 the specified URL (usually http://localhost:5000). You will be greeted with a chat
 interface where you can start asking questions based on the restaurant's Q/A PDF, Parivahan's Q/A PDF, Election Commision's Q/A



## 📌Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## 📌Results and Metrics

 Here are some key metrics showing the improvements made:
 - **ResponseAccuracy:** Improved by X% after implementing Azure OpenAI embeddings.
 - **Latency Reduction:**  Reduced response time by X% using optimized vector storage in AstraDB.
 - **UserSatisfaction:** Increased user satisfaction by X% based on feedback.


## 🙌Contributing
We welcome contributions! Please follow these steps to 
contribute:
-  Fork the repository.
- Create a new branch.
- Make your changes.
- Submit a pull request.

##  ✅License
This project is licensed under the MIT License- see the LICENSE file for details.

##  📧Contact
For any questions or issues, please open an issue on GitHub or contact (anandaditya189@gmail.com)
