# Simple LangChain Chatbot with OpenAI API

This is a very basic LangChain chatbot that uses OpenAI's GPT-3.5-turbo model to answer user queries. This project is intended as a beginner's guide to creating a chatbot using LangChain and deploying it with Streamlit.

## Features
- Uses OpenAI's GPT-3.5-turbo model for generating responses.
- Simple user interface with Streamlit.

## Prerequisites
- Python 3.7 or higher
- Git
- An OpenAI API key
- A LangChain API key

## Setup Instructions

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/USERNAME/REPOSITORY_NAME.git
cd REPOSITORY_NAME
```

### 2. Create a Virtual Environment
It's recommended to use a virtual environment to manage dependencies:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies
Install the required packages using pip:
```bash
pip install -r requirements.txt
```

### 4.  Create a .env File
Create a .env file in the project directory and add your OpenAI and LangChain API keys:
```bash
LANGCHAIN_API_KEY=your_langchain_api_key_here
OPENAI_API_KEY=your_openai_api_key_here
LANGCHAIN_PROJECT=chatbot-1
```

### 5. Run the Application
You can start the Streamlit application by running:
```bash
streamlit run app.py
```

### Usage
- Open your browser and go to the URL provided by Streamlit (usually http://localhost:8501).
- Enter a topic or question in the input box and press Enter.
- The chatbot will display the generated response.

### Project Structure
app.py: The main application file that sets up the Streamlit interface and integrates the LangChain and OpenAI API.
requirements.txt: A file containing all the dependencies required to run the application.

### Notes
This is a very basic example intended for beginners. For more advanced features and customizations, refer to the official documentation of LangChain and OpenAI.

### Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

### License
This project is licensed under the Apache 2.0 License.

