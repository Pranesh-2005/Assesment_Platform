# 📝 Assesment_Platform

Welcome to **Assesment_Platform**! This project provides a robust foundation for building online assessment and examination portals using Flask. It is designed to be extensible, user-friendly, and secure, making it ideal for educational institutions, training centers, or anyone who needs to manage and conduct online tests.

---

## 🌟 Introduction

Assesment_Platform is a web-based solution for creating, managing, and conducting online assessments. It leverages Python's Flask framework for the backend and delivers a modern, responsive user interface with HTML, CSS, and JavaScript. Whether you are an educator, trainer, or developer, this platform can help streamline your examination process.

---

## 🚀 Features

- **User Authentication & Sessions**: Secure login system with session management.
- **Question Paper Management**: Add, edit, and organize question papers easily.
- **Exam Portal**: Interface for students to attempt exams.
- **Dashboard**: Intuitive dashboard for admins and students.
- **Responsive Design**: Mobile-friendly UI using modern CSS.
- **Role-based Access**: Differentiated functionality for students and admins.
- **Help & Documentation**: Built-in help section for users.
- **Extensible Structure**: Modular codebase for easy customization.

---

## 🛠️ Installation

Follow these steps to set up the project locally:

### Prerequisites

- Python 3.7+
- `pip` package manager
- [Git](https://git-scm.com/)

### Steps

1. **Clone the Repository**
    ```bash
    git clone https://github.com/Pranesh-2005/Assesment_Platform.git
    cd Assesment_Platform
    ```

2. **Create a Virtual Environment (Recommended)**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Set Up Environment Variables**

    Create a `.env` file (or set environment variables) with:
    ```env
    FLASK_APP=app.py
    FLASK_ENV=development
    SECRET_KEY=your_secret_key
    ```

5. **Initialize the Database**

    > The platform uses SQLite by default. You may need to create the database and tables before first run. 
    ```bash
    flask db upgrade
    ```

6. **Run the Application**
    ```bash
    flask run
    ```

7. **Access the Portal**

    Open [http://localhost:5000](http://localhost:5000) in your browser.

---

## 📚 Usage

- **Login/Register**: Access the login page at the root URL. Register as a new user or login if already registered.
- **Admin Functions**: As an admin, you can add/edit exams, manage question papers, and view analytics.
- **Student Functions**: Students can access available exams, attempt questions, and view results.
- **Help Section**: Visit the Help page for guidance on using the platform.

> For more details, refer to the documentation or built-in help section.

---

## 🤝 Contributing

We welcome contributions from the community!

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a Pull Request.


---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

> **Thank you for checking out Assesment_Platform!**  
> Feel free to open issues or contribute to improve the project. Happy Assessing! 🚀

---

## 📁 Project Structure

```
Assesment_Platform/
│
├── app.py
├── static/
│   ├── css/
│   │   ├── dash.css
│   │   └── style.css
│   └── js/
│       └── script.js
├── students/
│   └── templates/static/css/dash.css
├── templates/
│   ├── add_question_paper.html
│   ├── examportal.html
│   ├── exams.html
│   ├── help.html
│   └── index.html
└── requirements.txt
```

---

> _For questions or support, please open an issue on GitHub._

## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/Pranesh-2005/Assesment_Platform
