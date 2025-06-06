# 🥤 VendingMachine App

A full-stack vending machine simulation app built with **React**, **Flask**, and **PostgreSQL**. Users can interact with a virtual vending machine frontend while the backend handles data via a REST API and database.

## 🚀 Tech Stack

- **Frontend:** React.js, TailwindCSS  
- **Backend:** Flask (Python), Flask-RESTful  
- **Database:** PostgreSQL  
- **Tools:** pgAdmin, psycopg2, VS Code  

## 🖥 Features

- 🎯 Interactive vending machine UI  
- 💾 Persistent product data with PostgreSQL  
- 🔄 REST API powered by Flask  
- ⚙️ Backend SQL utility functions for automation  

## 🛠 Getting Started

### 📌 Prerequisites

- Python 3.11+  
- Node.js + npm  
- PostgreSQL 14+  
- VS Code or similar IDE  
- pgAdmin (optional for DB UI)  

### 🔧 Backend Setup (Flask)

1. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Create a `db.yml` file inside the `api/` directory with your own PostgreSQL credentials:
   ```yaml
   host: localhost
   database: your_database_name
   user: your_database_user
   password: your_database_password
   port: 5432
   ```
   > 🔒 **Important:** Do not share this file or commit it to version control. Be sure to add `db.yml` to your `.gitignore`.

3. Run the backend server:
   ```bash
   python server.py
   ```

Access the API at: `http://localhost:5000`

### 🎨 Frontend Setup (React)

1. Install frontend packages:
   ```bash
   npm install
   ```

2. Start the React app:
   ```bash
   npm start
   ```

View the app in your browser at: `http://localhost:3000`

## 📍 Note

This project currently runs locally. Deployment is not configured yet.

## 📬 Contact

Have questions or suggestions?

- Created by **Jasmine Rmaidi**  
- Connect via GitHub or email


