# 🧠 Mental Health Chatbot 🤖  

A compassionate AI-powered chatbot designed to assist users with mental health-related questions. Built using **LangChain**, **Groq API**, **HuggingFace Embeddings**, and **ChromaDB**, this chatbot provides meaningful and thoughtful responses to user queries.  

🚀 **Features**  
- Uses **Llama-3.3-70B** via **Groq API** for intelligent responses  
- Processes **PDF-based mental health resources** and stores them in **ChromaDB**  
- Uses **HuggingFace BGE** embeddings for semantic search  
- Built with **Gradio** for an interactive chatbot UI  
- Provides **instant, supportive conversations** while respecting user privacy  

---

## 🔧 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/mental-health-chatbot.git
cd mental-health-chatbot
2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Set Up Environment Variables
Create a .env file in the project root and add your Groq API Key:

env
Copy
Edit
GROQ_API_KEY=your_groq_api_key_here
4️⃣ Run the Chatbot
bash
Copy
Edit
python app.py
This will start a Gradio interface where you can chat with the AI.

📚 How It Works
Loads mental health-related PDFs and converts them into vector embeddings.

Stores embeddings in ChromaDB for efficient retrieval.

Uses Groq API (Llama-3.3-70B) to generate thoughtful responses.

Provides responses via Gradio ChatInterface.

📸 Demo Screenshot

🤝 Contributing
We welcome contributions! Feel free to fork this repository and submit a pull request.

📜 License
This project is licensed under the MIT License.

💌 Contact
For any questions or support, please reach out via:
📧 Email: your-email@example.com
