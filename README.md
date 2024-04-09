# DocEmbed AI Search Engine

## Overview
The DocEmbed AI Search Engine is a powerful tool that allows you to search and retrieve relevant documents from a large corpus using natural language processing and document embedding techniques. With this application, you can easily find the information you need from your PDF files, without the need to manually sift through large amounts of text.

## Features
- **Semantic Search**: The search engine uses advanced natural language processing algorithms to understand the context and meaning of your queries, allowing you to find relevant documents even if the specific keywords are not present.
- **Document Embedding**: The application leverages document embedding techniques to represent the content of your PDF files in a high-dimensional vector space, enabling efficient similarity-based searches.
- **Contextual Answers**: The search engine not only retrieves relevant documents but also provides detailed answers to your questions, drawing from the content of the documents.
- **Streamlit Interface**: The application is built using the Streamlit framework, providing a user-friendly and interactive web-based interface for easy access and usage.

## Getting Started
To get started with the DocEmbed AI Search Engine, follow these steps:

1. **Clone the Repository**: Clone the project repository to your local machine.
2. **Install Dependencies**: Install the required dependencies by running the following command in your terminal:
   ```
   pip install -r requirements.txt
   ```
3. **Set up the Environment**: Create a `.env` file in the project directory and add the following environment variable:
   ```
   GOOGLE_API_KEY=your_google_api_key
   ```
   Replace `your_google_api_key` with your actual Google API key.
4. **Run the Application**: Start the Streamlit application by running the following command:
   ```
   streamlit run DocEmbedAI.py
   ```
5. **Upload PDF Files**: In the Streamlit interface, use the file uploader in the sidebar to upload your PDF files.
6. **Ask Questions**: Once the PDF files are processed, you can enter your questions in the text input field and the search engine will provide the relevant answers.

## Usage
The DocEmbed AI Search Engine is designed to be user-friendly and intuitive. Here's a step-by-step guide on how to use the application:

1. **Upload PDF Files**: Use the file uploader in the sidebar to upload your PDF files. The application will process the files and extract the text content.
2. **Ask Questions**: After the PDF files are processed, you can enter your questions in the text input field. The search engine will then provide the relevant answers based on the content of the documents.
3. **View Responses**: The application will display the responses to your questions, drawing from the context of the uploaded PDF files.

## Contributing
We welcome contributions to the DocEmbed AI Search Engine project. If you would like to contribute, please follow these steps:

1. **Fork the Repository**: Fork the project repository to your own GitHub account.
2. **Create a Branch**: Create a new branch for your feature or bug fix.
3. **Implement Changes**: Implement your changes and ensure that the application is still functioning correctly.
4. **Submit a Pull Request**: Create a pull request from your branch to the main repository, detailing the changes you have made.
