
# 🧠 Sentiment Analysis Project

This project demonstrates **Sentiment Analysis** using two approaches:

1. **Web-based Implementation** (HTML, CSS, JavaScript + Streamlit UI)  
   → A simple interactive interface to analyze text sentiment.  
   → Allows both single text analysis and bulk CSV file upload for batch sentiment analysis.

2. **Python-based Implementation**  
   → Uses Python libraries (`re`, `json`, `typing`) for advanced text sentiment classification.  
   → Easily extendable for more complex NLP tasks.

---

## 🚀 Features

- 🔹 **Single Analysis:** Enter a text snippet and instantly classify it as *Positive*, *Negative*, or *Neutral*.  
- 🔹 **Bulk Analysis:** Upload a CSV file containing text column(s) for large-scale sentiment analysis.  
- 🔹 **Web-based Dashboard:** Clean UI built using *Streamlit* + *HTML/CSS/JS*.  
- 🔹 **Lightweight Python Backend:** Handles text cleaning and sentiment detection efficiently.  
- 🔹 **Exportable Results:** Download processed CSV files after bulk analysis.

---

## 🛠 Project Requirements

To run this project locally, you’ll need:

- **Python 3.10+**  
  [Download Python 3.10 here](https://www.python.org/downloads/release/python-3100/)

- **Virtual Environment** (recommended)

- **Required Python Libraries:**
```

streamlit
pandas
re
json
typing

````

Install dependencies with:
```bash
pip install -r requirements.txt
````

---

## 📂 Database / Data Setup

No heavy database is required for this project.

* For **Single Text Analysis**, input is directly processed.
* For **Bulk Analysis**, upload a CSV file with at least one column containing text data.

**Example CSV format:**

```csv
id,text
1,This product is amazing!
2,I'm not happy with the service.
3,It was okay, nothing special.
```

---

## 💻 How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone <your-repo-link>
cd Sentiment-Analysis
```

### 2. Create & Activate Virtual Environment

**Windows**

```bash
py -3.10 -m venv venv
venv\Scripts\activate
```

**Mac/Linux**

```bash
python3.10 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App

Make sure you’re in the project root folder where `sentiment_app.py` is located:

```bash
streamlit run sentiment_app.py
```

### 5. Open in Browser

Once started, Streamlit will give a local URL, usually:

```
👉 http://localhost:8501
```

---

## 📸 Outputs

* **Single Analysis:** Enter a sentence → click *Predict* → sentiment displayed.
* **Bulk Analysis:** Upload CSV → view sentiment classification table + chart instantly.

---

## 🔮 Future Enhancements

* 🤖 Integrate Machine Learning models (Naive Bayes, LSTM, Transformers).
* 📊 Add Sentiment Intensity Score (not just Positive/Negative/Neutral).
* 🌐 Multi-language support.

---


