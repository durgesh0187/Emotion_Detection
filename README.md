# 🧠 Emotion Detection from Text

This is a Machine Learning-based web app that detects human emotions (like *happy*, *sad*, *angry*, etc.) from textual input using NLP techniques.

Built using:
- Python 🐍
- Scikit-learn 🤖
- TfidfVectorizer
- Streamlit 🚀
- NeatText for text preprocessing

---

## 🌐 Live Demo

🔗 [Click here to try the live app](https://emotiondetection-1.streamlit.app)

---

## 🎯 Features

- Predicts emotions from text
- Clean UI using Streamlit
- Confidence scores visualized with bar charts
- Text preprocessing using `neattext`
- Trained model with `LogisticRegression` and `TfidfVectorizer`

---

## 🛠️ How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/durgesh0187/emotion-detection-app.git
cd emotion-detection-app

# 2. Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
streamlit run app.py
