# ConvoCheck

ConvoCheck is an AI-powered discussion analysis platform that helps users quickly understand conversations by generating intelligent summaries, detecting sentiment, and identifying toxic content. The platform promotes safer and more productive online communication through automated moderation and AI-driven insights.

## Features

### 📄 AI-Powered Discussion Summarization

* Generates concise summaries of long conversations using Google's Gemini AI.
* Highlights the main points and discussion outcomes.

### Sentiment Analysis

* Detects the overall sentiment of a discussion.
* Categorizes conversations as:

  * Positive
  * Negative
  * Neutral

### Toxicity Detection & Moderation

* Identifies offensive or inappropriate language using profanity filtering.
* Flags potentially harmful comments for moderation.

### Real-Time Discussion Analytics

* Total Comments Count
* Safe Comments Count
* Toxic Comments Count
* Toxicity Percentage
* Overall Sentiment

### Modern Responsive UI

* Professional dashboard design.
* Dark-themed interface.
* Mobile and desktop compatible.

### Fast Processing

* Lightweight Flask backend.
* Instant analysis with minimal latency.

---

## Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### Backend

* Python
* Flask

### AI & NLP

* Google Gemini 2.5 Flash
* Better Profanity

### Deployment

* Vercel

---

## Project Structure

```text
ConvoCheck/
│
├── static/
│   ├── app.js
│   └── style.css
│
├── templates/
│   └── index.html
│
├── app.py
├── requirements.txt
├── .env
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/bstar042005/ConvoCheck-CanYouHackIt.git
cd ConvoCheck-CanYouHackIt
```

### 2. Create a Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root:

```env
GEMINI_API_KEY=your_gemini_api_key
```

### 5. Run the Application

```bash
python app.py
```

### 6. Open in Browser

```text
http://127.0.0.1:5000
```

---

## How It Works

1. Enter or paste discussion comments into the input box.
2. ConvoCheck analyzes the discussion using Gemini AI.
3. The system:

   * Generates a discussion summary
   * Detects overall sentiment
   * Identifies toxic comments
   * Calculates discussion statistics
4. Results are displayed in an interactive dashboard.

---

## Sample Use Case

### Input

```text
I love this product.
The service was terrible.
Support solved the issue.
```

### Output

* Summary of the discussion
* Positive overall sentiment
* Key discussion topics
* Toxicity analysis
* Comment moderation results

---

## Future Enhancements

* Advanced Toxicity Detection using Machine Learning
* Emotion Classification
* Multi-Language Support
* Conversation Trends Visualization
* User Authentication
* PDF Report Generation
* AI-Powered Moderation Suggestions
* Export Analysis Results

---

## Team Alpha Next

Developed by:

* Rajyavardhan Singh Rathore
* Bhavya Vaish
* Sharad Gupta

---

## GitHub Statistics

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is intended for educational, research, and hackathon purposes.
