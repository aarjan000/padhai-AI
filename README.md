Padhai AI - AI Quiz Maker

Padhai AI is an AI-powered quiz generation web application built using Python, Flask, and Groq. It helps students create multiple-choice quizzes from any topic or their own study notes.

 Features

- AI-powered quiz generation
- Generate quizzes from any topic
- Generate quizzes directly from personal notes
- Grounded question generation using provided study material
- Multiple-choice questions with four options
- AI-generated explanations for correct answers
- Customizable number of questions
- Structured JSON responses
- Simple and user-friendly web interface

Technologies Used

- Python
- Flask
- Groq API
- GPT-OSS-120B
- HTML
- JSON
- python-dotenv

How It Works

Padhai AI supports two quiz generation modes.

1. Topic-Based Quiz Generation

Enter a topic, choose the number of questions, and let the AI generate a quiz using its general knowledge.

 2. Notes-Based Quiz Generation

Paste your own study notes or paragraphs. The AI uses the provided material as its source to generate relevant questions.

This approach uses grounding to keep quiz generation focused on the supplied study material.

3. Project Structure

```text
padhai-ai/
│
├── main.py
├── templates/
│   └── index.html
├── .env
├── .gitignore
└── README.md
```

 Installation and Setup

 1. Clone the Repository

```bash
git clone https://github.com/aarjan000/padhai-AI.git
cd padhai-AI
```

 2. Install Dependencies

```bash
pip install flask groq python-dotenv
```

3. Configure Environment Variables

Create a file named `.env` in the project root directory.

Add your Groq API key:

```env
GROQ_API_KEY=your_groq_api_key
```

Replace the placeholder with your own Groq API key.

Never upload your `.env` file or expose your API key publicly.

 4. Run the Application

```bash
python main.py
```

 5. Open in Browser

Visit:

```text
http://127.0.0.1:5000
```

AI Model

Padhai AI currently uses GPT-OSS-120B through the Groq API for quiz generation and explanations.

 Future Improvements

- Interactive quiz interface
- Automatic answer evaluation
- Quiz scoring system
- Difficulty levels
- Support for PDF and document uploads
- User authentication
- Quiz history and progress tracking
- Improved question validation

 Author

Aarjan Acharya

GitHub: https://github.com/aarjan000
