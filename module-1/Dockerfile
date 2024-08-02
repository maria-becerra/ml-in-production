# Use the official Python image from the Docker Hub
FROM python:3.10

# Set working directory in the container
WORKDIR /app

# Copy requirements into the container
COPY requirements.txt .

# Install packages
RUN pip install --no-cache-dir -r requirements.txt

# Copy app.py
COPY app.py .

# Expose port 5000 to the outside world
EXPOSE 5000

# Define the command to run the application
CMD ["python", "app.py"]
