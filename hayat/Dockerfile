# Use official Python image as base
FROM python:3.9

# Set the working directory
WORKDIR /app

# Copy files
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . .

# Run the app
CMD ["python", "app.py"]
