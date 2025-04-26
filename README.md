🦜 Chat with SQL Database using LangChain and Streamlit
Welcome to Chat with SQL DB, a Streamlit-based application that lets you chat naturally with your SQLite or MySQL database using a powerful LLM model (Llama 3 via Groq API).
Easily explore, query, and interact with your database — without writing complex SQL queries manually!

🚀 Features
✅ Connect to a local SQLite3 database or your own MySQL database.

✅ Chat with your database using natural language.

✅ Powered by LangChain, Llama 3 (Groq API), and Streamlit.

✅ Clear conversation history anytime.

✅ Auto-switch between database types from the sidebar.

✅ Secure input for sensitive information (e.g., API keys, passwords).

📷 Screenshots

Home	Chatting
(Add your screenshots after uploading them to GitHub.)

🛠️ Installation
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/rog05/Chat-SQL/tree/main
cd Chat-SQL
2. Create a Virtual Environment (Optional but Recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
3. Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
4. Run the Application
bash
Copy
Edit
streamlit run app.py
🔑 Prerequisites
Python 3.8 or above

Groq API Key 

(Optional) A local student.db SQLite file or your own MySQL database credentials.

📋 Usage Instructions
Select the Database:

Use SQLite: It connects to student.db (must be placed in the same directory as the code).

Use MySQL: Enter host, user, password, and database name.

Enter Groq API Key in the sidebar.

Start Chatting:

Ask any question related to your database (e.g., "Show me all students with marks above 80").

The agent will generate and execute SQL queries automatically!

📦 Project Structure
bash
Copy
Edit
chat-with-sql-db/
│
├── app.py                  # Main Streamlit application
├── student.db               # SQLite database file (optional)
├── requirements.txt         # List of dependencies
├── README.md                # Project documentation
└── ...
🧩 Tech Stack
Frontend/UI: Streamlit

Backend/LLM: LangChain, Groq API (Llama 3)

Database: SQLite3 / MySQL

ORM/Connection: SQLAlchemy

⚠️ Important Notes
Database Security: Ensure sensitive database credentials are never committed to public repositories.

API Key Usage: Keep your Groq API Key secret and rotate it if exposed.

Performance Tip: SQLite connection is read-only. For large queries, prefer MySQL.

🙌 Acknowledgements
LangChain
Streamlit
Groq

⭐️ Give a Star!
If you like this project, please star ⭐️ the repository to support open-source work!
