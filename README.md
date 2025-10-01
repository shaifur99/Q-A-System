# Q-A-System
📚 Overview
This interactive Q&A system allows students to ask questions about their "English For Today - Class 5" textbook and get AI-powered answers based specifically on the textbook content.

🚀 Features
Textbook-based Answers: All responses are generated from the actual textbook content

Smart Search: Uses AI embeddings to find the most relevant textbook sections

Student-Friendly: Simple, clear answers suitable for Class 5 students

Interactive Interface: Easy-to-use question and answer format

🛠️ Setup Requirements
Required Libraries
python
python-docx
openai
scikit-learn
nltk
tiktoken
API Configuration
OpenAI API key required for AI functionality

Secure input method for API key protection

📖 How It Works
Upload Textbook: Upload your "English For Today.docx" file

Process Content: System automatically splits textbook into manageable chunks

Create Embeddings: AI generates semantic representations of textbook content

Q&A System: Ask questions and get textbook-based answers

💡 Usage
Starting the System
python
# Run the notebook cells in order
# Upload your textbook when prompted
# Enter your OpenAI API key securely
Asking Questions
Type your question about the textbook content

Get instant answers based on the actual textbook material

Use 'help' for example questions

Use 'sample' to see textbook content preview

Type 'exit' to quit

Example Questions
"What should we eat to be healthy?"

"Tell me about Saikat's family"

"What is the Food Pyramid?"

"How do we greet people in English?"

🔍 Technical Process
Text Processing

Reads Word document content

Splits into sentence-based chunks

Cleans and prepares text

Semantic Search

Creates embeddings for all text chunks

Uses cosine similarity to find relevant content

Retrieves top matching textbook sections

AI-Powered Answers

Combines relevant textbook content with question

Generates student-friendly responses

Ensures answers are textbook-accurate

📊 System Output
Textbook Analysis: Processes entire textbook (129,111+ characters)

Smart Chunking: Creates 479+ manageable text segments

Embedding Generation: 1536-dimensional vector representations

Real-time Q&A: Instant textbook-based responses

🎯 Educational Benefits
Personalized Learning: Get specific answers to individual questions

Textbook Accuracy: All answers verified against actual textbook content

24/7 Availability: Study assistance anytime

Confidence Building: Encourages curiosity and exploration

⚠️ Important Notes
Requires valid OpenAI API key

Internet connection needed for AI services

Works only with "English For Today - Class 5" textbook

Answers limited to textbook content only

🆘 Help Commands
help - Show example questions

sample - Preview textbook content

exit - Quit the application

