# FastAPI Server

This repository contains the code for a FastAPI server. Follow the instructions below to set up the development environment.

## Getting Started - 

### 1. Clone the Repository

First, clone the repository to your local machine using Git
```
  https://github.com/swapnilgupta14/FastAPI-Server.git
```
### 2. Create Python Virtual Environment

#### 2.1 Using Terminal
  Create the virtual environment:
  ```
      python3 -m venv env
  ```
  Activate the virtual environment:
  ```
      source env/bin/activate
  ```  
#### 2.2 Using VS Code Command Palette:

  1. Open the Command Palette with Ctrl + Shift + P.
  2. Search for Python: Create Environment.
  3. Select venv.
  4. Select the Python interpreter you want to use.

### 3. Install Dependencies

  With the virtual environment activated, install the necessary dependencies using pip:
   ```
    pip install -r requirements.txt
   ```
  make sure you are in the current directory where requirements.txt is present in the application
### 4. Running the Server

To run the FastAPI server, use the following command:
    ```
  uvicorn main:app --reload
    ```
### 5. The server will be running at
```
http://127.0.0.1:8000/docs#/default
```
#### Note : To generate - requiremenrs.txt
```bash
pip freeze > requirements.txt
```
