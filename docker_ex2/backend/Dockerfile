# Use Python 3.8 slim as the base image
FROM python:3.8-slim

# Set the working directory
WORKDIR /usr/src/app

# Copy all files from the current directory to the working directory
COPY . .

# Install the Python dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5000
EXPOSE 5000

# Command to run the application
CMD ["python", "app.py"]