# Use a lightweight Python base image
FROM python:3.9-slim

# Set working directory
WORKDIR /home/data

# Copy the text files into the container
COPY IF.txt AlwaysRememberUsThisWay.txt /home/data/

# Copy the Python script into the container
COPY scripts.py /home/data/

# Install any dependencies (optional)
# RUN pip install --no-cache-dir -r requirements.txt

# Execute the Python script
CMD ["python", "/home/data/scripts.py"]
