# 🦹 Villain Trading Cards Database

A Flask web application demonstrating database integration with SQLAlchemy for managing villain trading cards. This project focuses on building and structuring a database to store villain character information.

![Languages](https://img.shields.io/badge/HTML-43.9%25-orange)
![Languages](https://img.shields.io/badge/CSS-30.9%25-blue)
![Languages](https://img.shields.io/badge/Python-25.2%25-yellow)

## 📋 Project Overview

This application demonstrates fundamental database concepts using Flask and Flask-SQLAlchemy. Users can view villain trading cards with data stored in and retrieved from a SQLite database.

### Key Features

- **Database Integration**: SQLAlchemy ORM for database management
- **CRUD Operations**: Create, read, update, and delete villain records
- **Flask Backend**: Python web framework for routing and logic
- **Responsive Design**: Mobile-friendly interface for viewing cards
- **Data Persistence**: SQLite database for storing villain information

## 🛠️ Technologies Used

- **Backend**: Python, Flask, Flask-SQLAlchemy
- **Database**: SQLite
- **Frontend**: HTML5, CSS3
- **ORM**: SQLAlchemy

## 📚 Learning Outcomes

This project demonstrates:

- Setting up Flask with SQLAlchemy
- Creating database models and schemas
- Performing CRUD operations with SQLAlchemy
- Connecting Flask routes to database queries
- Rendering database content with Jinja templates
- Managing database migrations and updates

## 🚀 Installation & Setup

### Prerequisites

Check if Python is installed:

**On Mac:**
```bash
python3 --version
```

**On Windows:**
```bash
python --version
```

Ensure you have Python 3.8 or higher installed (3.11 recommended). If you need to install Python on Windows, see [this guide](https://docs.google.com/document/d/14diNu_g6uhouBscRt8zIezolANTRQA6HobKRP4Lgu5Q/copy).

### Step 1: Clone the Repository

```bash
git clone https://github.com/CatYoung018/villain-trading-cards-04-start-building-your-database-starter.git
cd villain-trading-cards-04-start-building-your-database-starter
```

### Step 2: Create Virtual Environment

**On Mac:**
```bash
python3 -m venv venv
```

**On Windows:**
```bash
python -m venv venv
```

### Step 3: Activate Virtual Environment

**On Mac:**
```bash
source venv/bin/activate
```

**On Windows:**
```bash
source venv/Scripts/activate
```

Once activated, you'll see `(venv)` at the beginning of your terminal prompt.

### Step 4: Install Dependencies

```bash
pip install flask flask-sqlalchemy
```

### Step 5: Run the Application

**Without debugger:**
```bash
flask run
```

**With debugger (recommended for development):**
```bash
flask run --debug
```

The app will run at: `http://127.0.0.1:5000/`

### Step 6: View the App

Open your browser and navigate to `http://127.0.0.1:5000/` to see the villain trading cards.

### Stopping the Application

- Press `Ctrl + C` to stop the server
- Run `deactivate` to close the virtual environment

**Note:** When not using the debugger, you'll need to stop and restart the server after making code changes. Remember to hard refresh your browser (`Ctrl + F5` or `Cmd + Shift + R`).

## 📁 Project Structure

```
villain-trading-cards-04-start-building-your-database-starter/
├── static/              # CSS, images, and static assets
├── templates/           # HTML templates (Jinja2)
├── app.py              # Main Flask application
├── .gitignore          # Git ignore file
├── README.md           # Project documentation
└── venv/               # Virtual environment (after setup)
```

## 🎯 Usage

1. **View Cards**: Navigate to the homepage to see all villain trading cards
2. **Database**: Villain data is stored in a SQLite database
3. **Add Cards**: Use the application routes to add new villain cards
4. **Update Cards**: Modify existing villain information through the interface
5. **Delete Cards**: Remove villain cards from the database

## 🔮 Future Enhancements

- Add search and filter functionality
- Implement user authentication
- Create admin panel for managing cards
- Add card rarity levels and stats
- Implement trading/collection features
- Add image upload for custom villain cards
- Export collection to PDF or CSV

## 🎓 Acknowledgments

This project was created as part of a Skillcrush coding bootcamp, focusing on database integration with Flask and SQLAlchemy.

## 📝 License

This project is open source and available for educational purposes.

## 📧 Contact

**Cat Young**  
Email: cat@catyoungconsulting.com  
Portfolio: [catyoung018.github.io/Cat-Young-Dev](https://catyoung018.github.io/Cat-Young-Dev/)  
GitHub: [@CatYoung018](https://github.com/CatYoung018)

---

⭐ **If you found this project helpful, please consider giving it a star!**

