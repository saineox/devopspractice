# Use an official Python runtime as the base image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# copy files -> file.py->container locaation .
COPY app.py .

#install required liabraries
RUN pip install Flask

#Run  Python compiled code
CMD ["python", "app.py"]
