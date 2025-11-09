# Q-A-System

## 📚 Overview
**Q-A-System** is an interactive question-and-answer platform designed for students of **"English For Today - Class 5"**. It allows students to ask questions and receive **AI-powered answers** derived specifically from the textbook content, ensuring accurate and relevant learning support.

---

## 🚀 Features
- **Textbook-Based Answers:** Responses are generated directly from the actual textbook content.  
- **Smart Search:** Utilizes AI embeddings to locate the most relevant sections of the textbook.  
- **Student-Friendly:** Provides simple, clear, and easy-to-understand answers for Class 5 students.  
- **Interactive Interface:** User-friendly question-and-answer format for smooth interaction.  

---

## 🛠️ Setup Requirements

### Required Libraries
- `python`
- `python-docx`
- `openai`
- `scikit-learn`
- `nltk`
- `tiktoken`

### API Configuration
- **OpenAI API key** is required for AI functionality.  
- Ensure secure handling of the API key to prevent unauthorized access.  

---

## 📖 How It Works
1. **Upload Textbook:** Upload the `"English For Today.docx"` file.  
2. **Process Content:** The system automatically splits the textbook into manageable chunks.  
3. **Create Embeddings:** AI generates semantic embeddings for each text chunk.  
4. **Q&A System:** Students ask questions and receive textbook-based answers instantly.  

---

## 💡 Usage

### Starting the System
```bash
# Run the notebook cells sequentially
# Upload your textbook when prompted
# Enter your OpenAI API key securely

Asking Questions

Type your question related to the textbook content.

Receive instant answers based on actual textbook material.

Use the following help commands:

help → Show example questions

sample → Preview textbook content

exit → Quit the application

Example Questions

"What should we eat to be healthy?"

"Tell me about Saikat's family"

"What is the Food Pyramid?"

"How do we greet people in English?"

🔍 Technical Process
Text Processing

Reads content from Word documents.

Splits content into sentence-based chunks.

Cleans and prepares text for embedding generation.

Semantic Search

Creates embeddings for all text chunks.

Uses cosine similarity to find the most relevant sections.

Retrieves top matching textbook segments.

AI-Powered Answers

Combines relevant textbook content with user questions.

Generates simple, student-friendly responses.

Ensures answers are textbook-accurate.

📊 System Output

Textbook Analysis: Processes over 129,111 characters.

Smart Chunking: Creates 479+ manageable text segments.

Embedding Generation: Produces 1536-dimensional vector representations.

Real-time Q&A: Provides instant, accurate answers.

🎯 Educational Benefits

Personalized Learning: Specific answers for individual questions.

Textbook Accuracy: Ensures content aligns with the textbook.

24/7 Availability: Offers study assistance anytime.

Confidence Building: Encourages curiosity and learning exploration.

⚠️ Important Notes

Requires a valid OpenAI API key.

Internet connection is necessary for AI services.

Works only with "English For Today - Class 5" textbook.

Answers are limited to textbook content only.

🆘 Help Commands
 | Command  | Description              |
| -------- | ------------------------ |
| `help`   | Show example questions   |
| `sample` | Preview textbook content |
| `exit`   | Quit the application     |
