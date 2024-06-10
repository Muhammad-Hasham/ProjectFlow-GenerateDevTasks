# ProjectFlow-GenerateDevTasks

## Prerequisites

Download and install Anaconda

## Setup Instructions

1. Open Anaconda Prompt.
2. Create a new environment (replace `<env>` with your desired environment name):
    ```sh
    conda create --name <env> python=3.11.5
    ```
3. Activate the environment:
    ```sh
    conda activate <env>
    ```
4. Cd into the `GenTasksBackend` folder in VS Code.
5. Select the newly created environment in VS Code:
   - Press `Ctrl+Shift+P` and select `Python: Select Interpreter`.
   - Choose the environment you created (e.g., `gptapienv`).

## Installation

Install the required packages:
```sh
pip install flask
pip install flask-cors
pip install openai==0.28.0
```

## Start the Application

python app.py
