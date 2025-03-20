# Athlete Sponsorship Management System

## 📌 Overview
The **Athlete Sponsorship Management System** is a web-based platform built using **Streamlit** that allows administrators and sponsors to manage athlete data, track performances, and handle sponsorships efficiently. The system enables role-based access for **Admins** and **Sponsors** to ensure smooth operations.

## 🚀 Features
### 🔹 Admin Features
- **Athlete Management**: Add, edit, delete athletes.
- **Performance Tracking**: Record yearly performances.
- **View Athletes & Performances**: View detailed athlete data and performance history.

### 🔹 Sponsor Features
- **Provide Sponsorship**: Assign sponsorships to athletes with details.
- **View Sponsorship**: Check sponsorship details for an athlete.
- **View Athletes & Performances**: Browse through athlete records and their performances.

## 🛠 Tech Stack
- **Frontend & UI:** Streamlit (Python-based Web Framework)
- **Backend:** Python (with JSON for data storage)
- **Data Storage:** JSON file-based storage

## 📂 Project Structure
```
Athlete-Sponsorship-System/
│── athletes.json       # Stores athlete data and sponsorship records
│── arglete_app.py             # Main application file with Streamlit UI
│── README.md           # Project documentation
```

## 🚀 Installation & Setup
### 🔹 Prerequisites
Ensure you have the following installed:
- Python 3.x
- Streamlit

### 🔹 Steps to Run the Project
1. **Clone the Repository**
   ```bash
   git clone https://github.com/ankithverma04/Athlete-Sponsorship-System.git
   cd Athlete-Sponsorship-System
   ```
2. **Create a Virtual Environment** (Optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate     # For Windows
   ```
3. **Install Dependencies**
   ```bash
   pip install streamlit
   ```
4. **Run the Application**
   ```bash
   streamlit run main.py
   ```
5. **Access the Application**
   The application will open in your default browser at:
   [http://localhost:8501/](http://localhost:8501/)

## 🤝 Contribution Guidelines
- Fork the repository.
- Create a new branch (`feature-branch` or `bugfix-branch`).
- Commit changes and push to GitHub.
- Open a pull request

  
---
**🚀 Happy Coding!** 🎯

