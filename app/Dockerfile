# Sets up container with Python 3.10 installed.
FROM python:3.9-bookworm

#copies everything in our current directory to the /app directory in the container.
COPY . /app

# Setting /app as the working directory for any RUN, CMD , ENTRYPOINT or COPY instructions. 
WORKDIR /app

# This install all packages listed in requirements.txt
RUN pip install -r requirements.txt

# Port in which streamlit app will run
EXPOSE 8501

#Command to run Streamlit app
CMD ["streamlit", "run", "main.py"]
