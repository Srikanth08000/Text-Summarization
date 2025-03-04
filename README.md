# 🦜 LangChain: Summarize Text from YouTube or Website

## 📌 Project Overview

This project is a **Streamlit-based web application** that leverages **LangChain** and **Groq API** to **summarize text content from YouTube videos or websites**. Users can simply enter a YouTube video URL or a webpage link, and the app will extract and summarize the text content in a **concise 300-word format**.

The application uses **LLMs (Large Language Models)** via **LangChain** to process and summarize text efficiently. It is built with **Streamlit** for an interactive UI, and includes URL validation, error handling, and a seamless user experience.

## 🚀 Features

- 📹 **Extracts and summarizes text from YouTube videos**.
- 🌍 **Supports webpage summarization** using an unstructured data loader.
- ⚡ **Uses LangChain and Gemma-7b-It model via Groq API**.
- 🎨 **Streamlit-based UI** for easy interaction.
- ✅ **Validates URLs before processing**.
- 🚀 **Handles errors to ensure smooth operation**.

## 🛠️ Tech Stack

- **Python** 🐍
- **Streamlit** 🎨
- **LangChain** ⚡
- **Groq API** 🌐
- **YouTubeLoader** 📹
- **UnstructuredURLLoader** 🌍

## 🔧 Getting Started

### 1️⃣ Prerequisites

Ensure you have the following installed:

- **Python 3.8+**
- **pip** (Python package manager)
- **Streamlit**
- **LangChain**
- **LangChain Community**
- **LangChain Groq**
- **Validators**
- **Unstructured**

### 2️⃣ Installation

Clone this repository and navigate to the project directory:

```sh
git clone https://github.com/your-username/your-repository.git
cd your-repository
Create a virtual environment (recommended):

sh
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

sh
Copy
Edit
pip install -r requirements.txt
3️⃣ Running the App
To launch the Streamlit application, run:

sh
Copy
Edit
streamlit run app.py
⚙️ Configuration
The app requires a Groq API Key to function. Enter the key in the sidebar of the app.

📝 Usage
🔗 Enter a YouTube Video URL or a Website URL in the provided field.
📌 Click "Summarize the Content from YT or Website".
⏳ Wait for the model to process and generate a summary.
✅ The summarized text will be displayed on the screen.
📌 Future Enhancements
🔍 Support for additional summarization models.
🎨 Enhanced UI/UX improvements.
📂 Ability to download summaries as text/PDF files.
🌍 Multi-language summarization support.
