🗄️ SQL Chatbot

📖 Overview

This project is a SQL-powered chatbot built with LangChain and Streamlit.
It allows you to query a database in natural language — the chatbot converts your question into SQL, executes it on either a local SQLite database (student.db) or a MySQL database, and returns the results in real time.

✨ Features

Chat interface powered by Streamlit

Supports SQLite (student.db included) and MySQL connections

Uses Groq LLM (Llama3-8b-8192) for natural language → SQL conversion

Maintains chat history across queries

Safe handling of MySQL credentials (via URL encoding)

🛠️ Project Structure

app.py → Main Streamlit app; connects to SQLite/MySQL and runs the chatbot.

sqlite.py → Script to create and populate the STUDENT table in student.db.

student.db → Preloaded SQLite database with sample student data.
