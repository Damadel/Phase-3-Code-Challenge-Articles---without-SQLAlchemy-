# 📰 Articles Code Challenge

A Python application that models **Authors**, **Articles**, and **Magazines** using the built-in `sqlite3` module and raw SQL queries — without using SQLAlchemy or any external libraries.

This project demonstrates object-oriented programming (OOP), raw SQL, and relational database design using Python only. It's ideal for practicing core backend development concepts with class relationships and simple data querying.

---

## 📁 Project Structure

Trev-our-Articles--without-SQLAlchemy-main/
├── lib/
│ ├── db/
│ │ ├── schema.sql # SQL table definitions
│ │ ├── seed.py # Insert sample data
│ │ └── connection.py # Database connection
│ ├── models/
│ │ ├── author.py # Author class
│ │ ├── article.py # Article class
│ │ └── magazine.py # Magazine class
│ └── debug.py # Run and print verification results
├── scripts/
│ ├── setup_db.py # Setup database from schema
│ └── run_queries.py # Custom SQL query logic
├── tests/ # Model test files
├── articles.db # SQLite database file (auto-created)
├── env/ # Virtual environment (optional)
├── .gitignore
└── README.md


---

## ✅ Features

- **Raw SQL**: No ORM — only native SQL queries.
- **OOP Modeling**: Classes for Author, Article, Magazine.
- **Relationship Methods**: Access related data (e.g., author.articles()).
- **Database Seeding**: Sample data included.
- **Debug Script**: Easy testing with `debug.py`.

---

## ⚙️ Setup Instructions

```bash
# 1. Clone the repository
git clone <your-repo-url>
cd Trev-our-Articles--without-SQLAlchemy-main

# 2. Create and activate a virtual environment
python3 -m venv env
source env/bin/activate    # For Windows: env\Scripts\activate

# 3. Run the debug script to verify setup
python lib/debug.py


