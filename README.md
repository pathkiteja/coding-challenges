# 📚 Question Bank - Flask Web App

A Flask-based web application that serves coding questions dynamically. The project is built with **Python (Flask)** and deployed using **Vercel**. The app includes an API endpoint for fetching questions and an interactive UI to display them.

---

## 🚀 Features

- **Dynamic Coding Questions** – Fetch and display coding-related questions.
- **Flask Backend** – Lightweight and scalable web framework.
- **API Integration** – Serve JSON-based question data.
- **Serverless Deployment** – Hosted on Vercel using serverless functions.
- **Interactive UI** – Uses HTML + Jinja2 templates to render questions.
- **Git Version Control** – Tracked using Git and GitHub for smooth collaboration.

---

## 📂 Project Structure

```plaintext
/question-bank
│── templates/                # HTML Templates
│   ├── index.html            # Home page
│   ├── view_questions.html   # Questions display page
│
│── app.py                    # Main Flask application
│── index.py                  # Alternative entry point
│── requirements.txt          # Dependencies for deployment
│── vercel.json               # Vercel configuration file
│── .gitignore                # Ignore unnecessary files
│── README.md                 # Documentation file (this file)

🛠 Installation & Setup
git clone https://github.com/pathkiteja/coding-challenges.git
cd coding-challenges

python -m venv venv
source venv/bin/activate  # For Mac/Linux
venv\Scripts\activate     # For Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Flask Application
python app.py

check my youtube channel 
