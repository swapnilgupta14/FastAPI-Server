# FastAPI Server

This repository contains the code for a FastAPI server. Follow the instructions below to set up the development environment.

## Getting Started

### 1. Clone the Repository

First, clone the repository to your local machine using Git:


### 2. Create Python Virtual Environment

#### Using Terminal:
  Create the virtual environment:
      python3 -m venv env
  Activate the virtual environment:
      source env/bin/activate
        
##### Using VS Code Command Palette:

  Open the Command Palette with Ctrl + Shift + P.
    Search for Python: Create Environment.
    Select venv.
    Select the Python interpreter you want to use.

### 3. Install Dependencies

  With the virtual environment activated, install the necessary dependencies using pip:
    pip install -r requirements.txt

### 4. Running the Server

To run the FastAPI server, use the following command:
  uvicorn main:app --reload
