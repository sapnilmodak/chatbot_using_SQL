# Chatbot with SQL Database 💬📊

A conversational chatbot built using **LangChain**, **GroqAI**, and **SQL Database** integration, designed to chat with users while querying and interacting with an SQL database. The chatbot leverages advanced AI models to generate dynamic responses based on user queries, enabling efficient data retrieval and enhanced user experience.

## 🚀 Features

- **Conversational Interface** 💬: The chatbot interacts with users in real-time, providing intelligent responses.
- **SQL Database Integration** 🗄️: Queries are executed on a connected SQL database (SQLite or MySQL), allowing users to access and retrieve data.
- **Real-time Chat History** 📜: Keeps track of conversation history for better context and personalization.
- **Custom Tool Integration** 🔧: Built-in tools like **Wikipedia** and **LLMathChain** to enrich user queries with external information.

## 🛠️ Tech Stack

- **LangChain**: For constructing the conversational AI pipeline and integrating external tools.
- **GroqAI**: For utilizing large language models to generate intelligent responses.
- **SQL Database (SQLite/MySQL)**: Stores and retrieves data dynamically based on user queries.
- **Streamlit**: For creating an interactive web interface for real-time user interactions.
- **Python**: The programming language powering the backend and AI models.

## 📝 Setup Instructions

### 📋 Prerequisites

Ensure you have the following:

- Python 3.7 or higher
- **GroqAI API Key** for accessing Groq models
- An SQL database (SQLite or MySQL) configured with appropriate credentials

### 💻 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chatbot-with-sql.git
### 🔍 How It Works
User Interaction 🗨️: The user inputs a query through the chatbot interface.
AI Processing 🤖: The chatbot uses GroqAI to understand and process the query.
SQL Query Execution 🗃️: Based on the user input, the chatbot queries the connected SQL database for relevant information.
Real-time Response ⚡: The chatbot dynamically generates a response based on both the database and conversation history, providing an intelligent reply.
Chat History 🗒️: The conversation context is saved and updated in real-time, improving the chatbot’s ability to remember previous interactions.
### 🖥️ Demo
Check out the demo of the Chatbot with SQL hosted on [https://chatbotusingsql.streamlit.app/].
