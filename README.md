# 📝Welcome to Todo List App!📝

This project provides a simple to-do list application using Python FastAPI and MongoDB on the backend, Streamlit on the frontend and Dockerization, creating a todo list for a daily use.

## Features: 

- Add Todo's
- View Todos
- Update Todos
- Delete Todos
- Mark Todo's as completed


### Prerequisites

- Docker 
- Docker Compose


## Code Structure 🔨:

### Backend (main.py + mongodb.py) :
 Contains Python code for the FastAPI backend (main.py), managing TODO items using CRUD and interacting with MongoDB (mongodb.py).
### Frontend (ui.py):
 Contains Python code for the Streamlit frontend user interface.
### docker-compose.yml:
 Defines the services (backend, frontend, and MongoDB) and their configuration for running with Docker Compose.



## ✨Installation✨:

1. **Clone this repository**:

```bash
git clone https://github.com/EASS-HIT-PART-A-2024-CLASS-IV/todolist-app.git
```
```bash
cd todolist-app
```

2. **Build the Docker containers**:

```bash
docker-compose build 
```

3. **run Docker Containers**:
  ```bash
docker-compose up -d 
```
4. **to check containers status using:**
```bash
docker-compose ps -a
```

## Using the App 👽:

**Open your web browser and navigate to:**
http://localhost:8501 to access the Streamlit interface for your Todo list.
  
## Access the App Components🌎:
- **Frontend:** http://localhost:8501
- **Backend:** http://localhost:8000/docs  --> to access API of the todo list app.

 
## Using the Test Script💯:
This project includes a test script (test.py) in the backend folder for testing the functionality of the backend API.

### Run Tests (using Docker Compose):

```bash
docker exec -it  <container_name_or_id> pytest /backend/test.py
```
where docker **<container_name_or_id>** is the backend container name, which you can find out by : 
**docker-compose ps -a**
<img width="865" alt="Untitled1" src="https://github.com/EASS-HIT-PART-A-2024-CLASS-IV/todolist-app/assets/88145461/566242fe-e8ff-4329-b04c-6d1eca2ca1dc">


This will execute the tests within a temporary container based on the configuration in docker-compose.yml. 

## Demo🎥:

https://github.com/EASS-HIT-PART-A-2024-CLASS-IV/todolist-app/assets/88145461/2f99428c-e5a1-46a0-81b2-55843493202f




