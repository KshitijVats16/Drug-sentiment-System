# Drug Sentiment Analysis & Reporting System

## Overview
This project is a web-based application that analyzes drug reviews and predicts sentiment (positive/negative) using machine learning.

It integrates natural language processing with a full-stack system to provide insights into patient feedback.

---

## Features
- Upload and preview drug review datasets
- User authentication (Login/Register)
- Sentiment prediction using ML model
- Store results in MySQL database
- Admin dashboard with sentiment visualization

---

## Tech Stack
- **Backend:** Flask (Python)
- **Machine Learning:** TF-IDF, LinearSVC (Scikit-learn)
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript
- **Visualization:** Chart.js

---

## How It Works
1. User uploads dataset or enters review
2. Text is cleaned and preprocessed
3. TF-IDF converts text into numerical features
4. ML model predicts sentiment
5. Results are stored in MySQL
6. Dashboard displays insights

---

## Setup Instructions

1. Clone the repository:
```
git clone https://github.com/KshitijVats16/Drug-sentiment-System.git
```

2. Navigate to the folder:
```
cd Drug-sentiment-System
```

3. Install dependencies:
```
pip install -r requirements.txt
```

4. Setup MySQL database:
- Import `database.sql`

5. Run the application:
```
python app.py
```

6. Open in browser:
```
http://127.0.0.1:5000
```

---

## Use Case
This system helps analyze patient feedback on drugs and supports data-driven insights for better decision-making.

---

## Author
Kshitij Vats
