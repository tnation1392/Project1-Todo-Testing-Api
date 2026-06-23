📌 Todo Testing API
A lightweight Python-based Todo API project designed to demonstrate API development and automated testing practices. This project focuses on validating CRUD operations and showcasing real-world QA workflows using automated tests.

🚀 Overview
This repository contains:

A simple Todo API (app.py)
A comprehensive test suite (test_api.py)
Dependency management (requirements.txt)

The goal of this project is to practice backend API testing, including:

Functional validation of endpoints
Automated testing with pytest
Verifying expected API behavior (status codes, responses, edge cases)


🧩 Features
✅ API Functionality

Create a new Todo
Retrieve all Todos
Retrieve a single Todo
Update a Todo
Delete a Todo

✅ Testing Coverage

Endpoint validation (GET, POST, PUT/PATCH, DELETE)
Response structure verification
Status code assertions
Edge case handling


🛠️ Tech Stack

Python
Flask or FastAPI
pytest
requests / test client


📂 Project Structure
todo-api-project/
│
├── app.py
├── test_api.py
├── requirements.txt
└── README.md


⚙️ Setup & Installation
1. Clone the Repository
git clone https://github.com/tnation1392/tnation1392-Project1-Todo-Testing-Api.git
cd tnation1392-Project1-Todo-Testing-Api
3. Create Virtual Environment
python -m venv venvsource venv/bin/activate        
4. Install Dependencies
pip install -r requirements.txtShow more lines

▶️ Running the Application
Start the API Server
python app.py

Runs locally at: http://127.0.0.1:5000
Accessible via browser, Postman, curl, or test suite


Example API Usage
Create a Todo
curl -X POST http://127.0.0.1:5000/todos \-H "Content-Type: application/json" \-d '{"title": "Learn API Testing"}'Show more lines
Get All Todos
curl http://127.0.0.1:5000/todosShow more lines
Update a Todo
curl -X PUT http://127.0.0.1:5000/todos/1 \-H "Content-Type: application/json" \-d '{"title": "Updated Task"}'Show more lines
Delete a Todo
curl -X DELETE http://127.0.0.1:5000/todos/1Show more lines

🧪 Running Tests
Run All Tests
pytestShow more lines
Verbose Mode
pytest -vShow more lines
Run Specific Test File
pytest test_api.pyShow more lines
Run One Test
pytest test_api.py::test_create_todoShow more lines

🎯 Learning Goals

API validation strategies
Automated backend testing
pytest usage in real scenarios
QA-focused development mindset


📈 Future Improvements

Add authentication (JWT)
CI/CD pipeline
Swagger/OpenAPI docs
Database integration
```

Add a clean endpoint table (looks great to recruiters)
Or generate a GitHub Actions CI file to auto-run pytest
