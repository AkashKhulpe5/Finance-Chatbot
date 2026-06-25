# Finance-Chatbot

Description
The Finance Chatbot is an intelligent AI assistant built to help users navigate complex financial topics with ease. By leveraging the speed and power of the Groq API, this application provides users with immediate, accurate, and concise financial information.

Unlike general-purpose chatbots, this tool is specifically engineered with a system-level constraint to focus exclusively on finance. It is designed to act as a personal financial tutor: not only does it provide answers, but it also explains the underlying logic, provides real-world examples, highlights necessary mathematical formulas, and offers guidance based on established financial principles. Whether you are learning about compound interest, budgeting, or investment strategies, this chatbot ensures that responses are informative and strictly relevant to your financial inquiries.

Key Features
Niche Specialization: Strictly scoped to handle financial queries; it identifies and declines unrelated topics.

Educational Clarity: Ensures complex financial concepts are broken down into simple, actionable examples.

Formulaic Accuracy: Automatically includes relevant mathematical equations (e.g., CAGR, ROI, Loan Amortization) when applicable.

Conversational Memory: Uses Streamlit’s session_state to track chat history, allowing for follow-up questions and deeper context.

Professional Guidance: Provides advice based on sound financial logic, helping users make informed decisions.

Tech Stack
Frontend: Streamlit for a clean, interactive, and responsive web interface.

LLM Engine: Groq API for high-performance inference.

Backend: Python.

Setup Instructions
1. Installation
Ensure you have the required dependencies installed:

Bash
pip install streamlit groq python-dotenv
2. Configuration
Create a config.py file in the root directory and add your credentials:

Python
GROQ_API_KEY = "your_actual_groq_api_key_here"
MODEL = "llama3-70b-8192" 
3. Execution
Launch the application by running the following command in your terminal:

Bash
streamlit run app.py
