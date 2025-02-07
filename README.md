# 🚀 Shortify-Py - URL Shortener

Shortify-Py is a simple URL shortener built using **Python (Flask)** and **SQLite**. It allows users to convert long URLs into short links and redirect them efficiently.

## 📌 Features
- Generate short URLs for long links 🔗
- Store URLs in an SQLite database 🗃️
- Redirect users from short links to original URLs 🚀
- Simple and easy-to-use web interface 🎨

## 🛠️ Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/shreyash0019/Shortify-Py.git
   cd Shortify-Py
   ```
2. **Install dependencies:**
   ```bash
   pip install flask flask-sqlalchemy
   ```
3. **Initialize the database:**
   ```bash
   python -c "from app import db; db.create_all()"
   ```
4. **Run the application:**
   ```bash
   python app.py
   ```
5. **Open your browser and visit:**
   ```
   http://127.0.0.1:5000/
   ```

## 📂 Project Structure
```
Shortify-Py/
│── app.py          # Flask backend logic
│── database.db     # SQLite database (auto-created)
│── templates/
│   ├── index.html  # Frontend for URL input   # Basic styling (optional)
└── README.md       # Project documentation
```

## ✨ Usage
- Enter a long URL in the input field.
- Click "Shorten" to generate a short link.
- Copy and share the shortened URL.

## 🤝 Contributing
Feel free to **fork** this repository and submit pull requests to improve the project!

## 📜 License
This project is licensed under the **MIT License**.

## 📧 Contact
For any issues or suggestions, open an issue in the repository or reach out via GitHub. 😊

