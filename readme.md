# pythonweb-hw-02: Basics of Docker Technology

## Setup

Create a virtual environment and install the required libraries:

```bash
pip install -r requirements.txt
```

## Running the Application

To run the application locally:

```bash
python main.py
```

## Running with Docker

1. Build and start the Docker containers:

   ```bash
   docker-compose up -d --build
   ```

2. Access the FastAPI application at `http://localhost:8000`.

3. Check the health checker endpoint at `http://localhost:8000/healthchecker`.

## Stopping the Application

To stop the Docker containers:

```bash
docker-compose down
```
