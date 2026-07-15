# 🎓 AI Learning Assistant

An AI-powered learning assistant that detects a student's emotional state while learning and provides personalized, empathetic guidance using Deep Learning and Large Language Models.

The system combines **BiLSTM**, **BERT**, and **Google Gemini 2.5 Flash** to understand student emotions and generate supportive learning recommendations.

---

## 🌟 Features

- 🎭 Emotion Detection using BiLSTM
- 🤖 Emotion Classification using Fine-tuned BERT
- 😊 Mixed Emotion Detection
- 🧠 Personalized AI responses using Gemini 2.5 Flash
- 📊 Side-by-side BiLSTM vs BERT comparison
- 📈 Confidence score visualization
- 📝 Session history tracking
- 💾 CSV logging for continuous learning
- 📚 Field-aware learning assistance
- ⚡ Interactive Streamlit interface

---

## 🏗️ Project Architecture

```
Student Input
      │
      ▼
Text Preprocessing
      │
      ▼
 ┌───────────────┐
 │ BiLSTM Model  │
 └───────────────┘
          │
          ▼
 ┌───────────────┐
 │  BERT Model   │
 └───────────────┘
          │
          ▼
 Mixed Emotion Detection
          │
          ▼
 Gemini 2.5 Flash
          │
          ▼
 Personalized Learning Guidance
```

---

# 📂 Project Structure

```text
AI_Learning_Assistant/
│
├── app.py
├── requirements.txt
├── README.md
├── .env
│
├── models/
│   ├── bert/
│   └── bilstm/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── interim/
│
├── src/
│   ├── bert_classifier.py
│   ├── emotion_predictor.py
│   ├── emotion_pipeline.py
│   ├── mixed_emotion_detector.py
│   ├── text_preprocessor.py
│   ├── keyword_enhancer.py
│   ├── history_manager.py
│   ├── csv_manager.py
│   ├── emotion_templates.py
│   └── train_*.py
│
└── notebooks/
```

---

# 🧠 Technologies Used

### Programming

- Python 3.11

### Machine Learning

- TensorFlow
- Keras
- PyTorch
- Hugging Face Transformers

### NLP

- BERT
- BiLSTM
- Tokenization
- Text Preprocessing

### Generative AI

- Google Gemini 2.5 Flash API

### Web Framework

- Streamlit

### Data Processing

- Pandas
- NumPy
- Scikit-learn

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git

cd YOUR_REPOSITORY
```

Create Virtual Environment

```bash
python -m venv .venv
```

Activate Environment

Windows

```bash
.venv\Scripts\activate
```

Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Configure Gemini API

Create a `.env` file

```text
GEMINI_API_KEY=YOUR_API_KEY
```

---

# ▶️ Run the Application

```bash
streamlit run app.py
```

---

# 🧪 Models Used

## BiLSTM

- Student emotion classification
- Softmax probability distribution
- Five emotion classes

## BERT

Fine-tuned Transformer model with:

- Class weighting
- Keyword enhancement
- Confidence adjustment

---

# 😊 Supported Emotions

| Emotion | Description |
|----------|-------------|
| 😕 Confused | Student is struggling to understand concepts |
| 😠 Frustrated | Student feels stuck or overwhelmed |
| 😎 Confident | Student understands the topic |
| 🤔 Curious | Student wants to explore further |
| 😴 Bored | Student has low engagement |

---

# 🤖 AI Guidance

Gemini generates personalized responses based on:

- Student's field
- Learning problem
- Detected emotion
- Confidence score

If Gemini is unavailable, the system automatically switches to predefined empathetic response templates.

---

# 📊 Application Features

- Emotion Prediction
- Mixed Emotion Detection
- BiLSTM vs BERT Comparison
- AI Learning Support
- Confidence Scores
- Session History
- CSV Analytics
- Dashboard
- Field-aware Recommendations

---

# 📈 Future Improvements

- Voice emotion detection
- Speech-to-text support
- Personalized learning analytics
- Learning progress dashboard
- Multi-language support
- Cloud deployment
- User authentication

---

# 📷 Screenshots

Add screenshots here after deployment.

Example:

```
<img width="1920" height="1017" alt="image" src="https://github.com/user-attachments/assets/55468839-2bc4-4039-b783-de256ee9fa66" />


<img width="1907" height="1003" alt="image" src="https://github.com/user-attachments/assets/a738120c-3b4d-4377-9634-814e448658da" />


```

---

# 👩‍💻 Authors

**Moravaneni Aiswarya Lakshmi**
**Gutha RamaKrirshna**
**Swathi Polavaram**

B.Tech Computer Science (Data Science)

Sri Venkateswara College of Engineering, Tirupati

GitHub: https://github.com/aiswarya08-moravaneni

LinkedIn: https://www.linkedin.com/in/moravaneni-aiswarya-lakshmi-93201a2a7

---

# 📄 License

This project is developed for educational and research purposes.
