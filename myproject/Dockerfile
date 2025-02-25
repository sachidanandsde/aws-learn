# Use official Python image as base
FROM python:3.9

# Set the working directory
WORKDIR /app

# Copy project files to the container
COPY . /app

# Install dependencies
RUN pip install

# Expose the port Django runs on
EXPOSE 8000

# Start the Django application without running migrations
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]