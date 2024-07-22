FROM python:3.8-alpine

# Set the working directory
WORKDIR /app

# Copy the requirements.txt file and install dependencies
COPY requirements.txt /app/
RUN pip install -r requirements.txt

# Copy the rest of the application code
COPY . /app

# Command to run the application
CMD ["python", "app.py"]
