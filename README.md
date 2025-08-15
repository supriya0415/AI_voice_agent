# AI Voice Agent 🎤🤖

An AI-powered voice assistant that can transcribe speech to text and generate human-like speech from text using advanced APIs like **AssemblyAI** and Murf.  
Built with Python and FastAPI, this project allows interactive voice communication between users and AI.

## 🚀 Features
- 🎙 **Speech-to-Text** – Converts spoken audio into text using AssemblyAI.
- 🗣 **Text-to-Speech** – Generates realistic voice from text using Murf API.
- 🌐 **FastAPI Backend** – High-performance server to handle API requests.
- 📜 **Interactive UI** – Simple and responsive interface for testing voice features.
- 🔒 **Secure API Keys Handling** – Uses `.env` file to store sensitive credentials.

## 🛠 Tech Stack
- **Backend:** Python, FastAPI
- **Frontend:** HTML, CSS, JavaScript
- **APIs:** AssemblyAI (Speech-to-Text), Murf (Text-to-Speech)
- **Version Control:** Git & GitHub

## 📂 Project Structure

AI\_voice\_agent/
│
├── static/         # CSS, JS, and static assets
├── templates/      # HTML templates
├── main.py         # FastAPI entry point
├── requirements.txt # Dependencies
├── .env.example    # Sample environment variables
└── README.md       # Project documentation

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/supriya0415/AI_voice_agent.git
   cd AI_voice_agent
````

2. **Create and activate a virtual environment**

   ```bash
   python -m venv venv
   venv\Scripts\activate   # For Windows
   source venv/bin/activate # For Mac/Linux
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set environment variables**

   * Create a `.env` file in the root folder:

     ```
     ASSEMBLYAI_API_KEY=your_api_key_here
     MURF_API_KEY=your_api_key_here
     ```

5. **Run the FastAPI server**

   ```bash
   uvicorn main:app --reload
  

6. **Open in browser**

   http://127.0.0.1:8000
  

## 🎯 Future Improvements

* Add multi-language speech support.
* Improve UI/UX with React or Vue.
* Add conversation memory.


## 📜 License

This project is licensed under the MIT License.
Kya mai screenshot wala section add kar du?
```
