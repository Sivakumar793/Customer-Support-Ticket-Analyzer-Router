# Customer-Support-Ticket-Analyzer-Router

This project implements an AI-powered system to **analyze and automatically categorize customer support tickets**, and **assign appropriate priority levels** based on multiple factors such as customer tier, sentiment, and issue type.

---

## 📂 Project Structure

- `Draconic_Ticket_Analyzer_Router.ipynb`: Main notebook demonstrating ticket analysis and routing using custom agents.
- `agents/classifier_agent.py`: Agent to classify the type of support issue (e.g., Bug, Feature Request).
- `agents/priority_agent.py`: Agent to assign priority (e.g., High, Medium, Low) based on ticket attributes.

---

## 📋 Features

✅ Classifies tickets into categories like:
- Bug Report
- Feature Request
- Account Issue
- UI Feedback
- Others

✅ Assigns ticket priority using:
- Customer tier (Free, Premium, Enterprise)
- Sentiment analysis (from message)
- Monthly revenue and account age

✅ Stores prediction results into a structured JSON file (`evaluation/results.json`)

---

## 🧪 Sample Tickets Used

The system analyzes multiple support tickets with attributes like:
- Subject and message body
- Monthly revenue
- Customer tier
- Previous ticket count
- Account age

---

## 🛠️ Technologies Used

- Python 🐍
- Scikit-learn
- Numpy, Pandas
- TextBlob (for sentiment analysis)
- Custom rule-based logic

---

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/Sivakumar793/Customer-Support-Ticket-Analyzer-Router.git
```

2. Run the Jupyter notebook:
```bash
jupyter notebook Draconic_Ticket_Analyzer_Router.ipynb
```

---

## 📈 Future Improvements

- Integrate LLMs or transformers for smarter classification
- Connect to real-time support systems (e.g., Zendesk, Freshdesk)
- Store results in a database

---

## 🧑‍💻 Author

Siva Kumar M

For AI/ML Engineer Case Study @ Draconic

---

