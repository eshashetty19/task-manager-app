# 📝 To-Do List App

A simple **To-Do List application** built with **Node.js (Express), EJS, PostgreSQL, HTML, and CSS**.  
This app allows users to add, view, and delete tasks with data stored in a PostgreSQL database.

---

##  Features

- Add new tasks  
- View all tasks in a list  
- Delete completed tasks  
- Persistent storage with **PostgreSQL**  
- Clean and responsive UI using HTML & CSS  
- Dynamic rendering with **EJS templates**

---

## Tech Stack

- **Backend:** Node.js, Express  
- **Frontend:** HTML, CSS, EJS  
- **Database:** PostgreSQL  

---

## Installation & Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/task-manager-app.git
    cd task-manager-app
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Setup PostgreSQL database:

    - Create a database (e.g., `todo_db`)  
    - Create a table:

    ```sql
    CREATE TABLE tasks (
      id SERIAL PRIMARY KEY,
      task TEXT NOT NULL
    );
    ```

4. Create a `.env` file in the project root:

    ```env
    DB_USER=your_username
    DB_HOST=localhost
    DB_NAME=todo_db
    DB_PASSWORD=your_password
    DB_PORT=5432
    ```

5. Start the app:

    ```bash
    node index.js
    ```

6. Open the app in your browser:  

    [http://localhost:3000](http://localhost:3000)
