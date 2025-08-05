# 📝 Registration and Login App (Node.js + MongoDB + EJS)

This is a simple full-stack web application that allows users to **register** and **log in**. It uses Node.js, Express, MongoDB, and EJS templating.

---

## 📁 Project Structure


---

## 🚀 Features

- User registration
- User login
- MongoDB data storage
- EJS for rendering views
- Environment configuration with `.env`

---
## 📁 Folder Structure
```
project-root/
├── config/
│ └── db.js
├── models/
│ └── register-model.js
├── node_modules/
├── views/
│ ├── login.ejs
│ ├── main.ejs
│ └── register.ejs
├── .env
├── .gitignore
├── index.js
├── package.json
├── package-lock.json
├── readme.md
```
### Structure Explanation:
- **`config/`** - Configuration files
  - `db.js` - Database connection settings
- **`models/`** - Data models
  - `register-model.js` - Registration related database operations
- **`views/`** - Front-end templates
  - `login.ejs` - Login page template
  - `main.ejs` - Main application page
  - `register.ejs` - Registration page template
- **Root files**:
  - `.env` - Environment variables
  - `.gitignore` - Git exclusion rules
  - `index.js` - Main application entry point
  - `package.json` - Project metadata and dependencies
 


## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/hitlargautam/your-repo.git
   cd your-repo

```
MONGO_URI=your_mongodb_connection_string
PORT=3000
