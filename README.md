# 📚 AI Study Planner

An intelligent study planning and productivity application built with **Python**, **Streamlit**, and **Groq AI**. This project helps students organize their study schedules, track learning progress, visualize study patterns through charts, and interact with an AI-powered study assistant.

---

## 🚀 Features

### 📖 Subject Management

* Add, edit, and manage study subjects.
* Organize subjects based on priority and importance.
* Maintain a structured study routine.

### ⏱️ Study Hours Tracking

* Log daily study hours.
* Monitor time spent on each subject.
* Track consistency and productivity over time.

### 📊 Interactive Analytics Dashboard

* Visualize study progress using charts and graphs.
* Analyze subject-wise study distribution.
* Monitor daily and weekly performance trends.
* Gain insights into learning habits.

### 🤖 AI Study Assistant

Powered by **Groq API**.

* Ask academic questions.
* Get explanations of difficult concepts.
* Generate study plans and revision strategies.
* Receive personalized learning suggestions.
* Interactive chatbot experience within the application.

### 🎯 Productivity Monitoring

* Track study goals.
* Measure progress against targets.
* Improve consistency and time management.

---

## 🛠️ Tech Stack

| Technology          | Purpose                   |
| ------------------- | ------------------------- |
| Python              | Backend Logic             |
| Streamlit           | Web Application Framework |
| Groq API            | AI Chat Assistant         |
| Pandas              | Data Handling             |
| Matplotlib / Plotly | Data Visualization        |
| NumPy               | Numerical Operations      |

---

## 📂 Project Structure

```bash
AI-Study-Planner/
│
├── app.py
├── requirements.txt
├── README.md
│
├── data/
│   └── study_records.csv
│
├── utils/
│   ├── tracker.py
│   ├── analytics.py
│   └── chatbot.py
│
├── assets/
│   └── images/
│
└── charts/
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/AI-Study-Planner.git
cd AI-Study-Planner
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Groq API Setup

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key_here
```

You can obtain an API key from the Groq Console.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will launch in your browser:

```bash
http://localhost:8501
```

---

## 📈 Example Use Cases

* Create personalized study schedules.
* Track preparation for exams.
* Monitor subject-wise study hours.
* Analyze study consistency.
* Ask AI for concept explanations.
* Generate revision plans.
* Improve productivity through data-driven insights.

---

## 🔮 Future Enhancements

* User Authentication
* Cloud Database Integration
* AI-Powered Performance Predictions
* Goal-Based Study Recommendations
* Calendar Integration
* Study Streak Tracking
* Export Reports as PDF
* Multi-User Support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed using **Python, Streamlit, and Groq AI** to make studying smarter, more organized, and more productive.

⭐ If you found this project useful, consider giving it a star on GitHub!
