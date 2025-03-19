# 📧 AI-driven Cold Email Generator

A Python project that leverages AI and data-driven automation to generate personalized cold emails for job seekers. This tool extracts job posting details from company career pages and creates impactful emails using state-of-the-art models and frameworks including Python, Streamlit, Groq, LangChain, and the versatile **Llama 3.3 lb model** (you can change this to another model if desired). It employs a Retrieval-Augmented Generation (RAG)-like approach by dynamically retrieving relevant portfolio links from a vector database based on job descriptions, thereby optimizing recruiter engagement and accelerating the job search process.

## Features

- **Automated Job Listing Extraction:**  
  Input a company's careers page URL to automatically extract job posting.
- **Personalized Email Generation:**  
  Generate tailored cold emails using advanced AI models.
- **Dynamic Portfolio Link Retrieval:**  
  Retrieve contextually relevant portfolio links from a vector database.
- **Scalable & Data-driven:**  
  Designed to streamline the job search process through automation.

## Technologies Used

- **Python:** Core programming language.
- **Streamlit:** Framework for creating an interactive web interface.
- **Groq:** API integration for extracting job posting details.
- **LangChain:** Framework for interfacing with language models.
- **Llama 3.3 lb Model:** Versatile AI model for generating high-quality, personalized emails. (This can be swapped with a different model if needed.)
- **Vector Database:** Stores and retrieves portfolio links based on job descriptions.

## Full Setup & Run Instructions

### Prerequisites

- Python 3.7 or higher installed on your machine.
- An active API key from [Groq](https://console.groq.com/keys).
- Access to a vector database for storing and retrieving portfolio links.

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `.env` update the value of `GROQ_API_KEY` with the API_KEY you created. (My API_KEY is already present in the .env file)


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run main.py
   ```
