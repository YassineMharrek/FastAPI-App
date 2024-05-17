# FastAPI Docker Example

## Description
This project demonstrates a simple FastAPI application containerized with Docker.

## Requirements
- Docker
- Python 3.7+
- pip

## Setup

1. Clone the repository:
    ```bash
    git clone <repository_url>
    cd fastapi-docker-example
    ```

2. Set up the virtual environment and install dependencies:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

## Running the Application

1. Build the Docker image:
    ```bash
    docker build -t fastapi-docker-example .
    ```

2. Run the Docker container:
    ```bash
    docker run -p 80:80 fastapi-docker-example
    ```

3. The application will be accessible at `http://localhost`.

## Running Tests

1. Ensure the virtual environment is activated:
    ```bash
    source venv/bin/activate
    ```

2. Run the tests using pytest:
    ```bash
    pytest
    ```

## Additional Notes
Feel free to enhance the application with additional features or endpoints if time permits.
