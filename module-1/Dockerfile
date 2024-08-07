FROM python:3.12-slim

# set working dir
WORKDIR /app

# copy requirement file
COPY requirements.txt .

# Install the required packages
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

# commands to run the application
CMD ["python", "hello_docker.py"]
