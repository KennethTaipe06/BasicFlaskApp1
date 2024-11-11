# Python Flask Basic App

This is a basic Flask project created as part of a Distributed Programming assignment. For this assignment, we used five different programming languages across five individual projects to demonstrate and explore various technologies and methods.

## Table of Contents

- [Project Description](#project-description)
- [Requirements](#Requirements)
- [Installation and Local Setup](#installation-and-local-setup)
- [Usage](#Usage)
- [Docker](#docker)

## Project Description

This project involves creating a simple Flask web application that displays a basic homepage with the message, "It works!!! 1/5 Python."

### Features:
- Basic setup of a Flask application
- A homepage that displays "It works!!! 1/5 Python."
- Dependency management with a `requirements.txt` file

## Requirements

Before you begin, ensure you have the following installed:

- Python 3.12.0 or higher: [Download Python](https://www.python.org/downloads/)
- Flask: The Python web framework (installed via `requirements.txt`)

## Installation and Local Setup

Follow these steps to set up the project on your local machine:

1. **Clone the repository** to your local machine:
    ```bash
    git clone https://github.com/KennethTaipe06/BasicFlaskApp1.git
    ```
2. **Open a Powershell terminal** in the project directory.
3. **Navigate to the project directory** on your local machine:
    ```bash
    cd .\flaskapp-vercel\
    ```


4. **Activate the virtual environment**:
    ```bash
    .\venv\Scripts\activate
    ```
5. **Install dependencies** from `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once the dependencies are installed, run the Flask application with the following command:
```bash
python app.py
 ```
Access the application: http://localhost:5000
## Docker
if you want to run a docker image of this proyect you should go:
- [Docker Hub](https://hub.docker.com/r/byvoxel/python5)
