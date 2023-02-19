FROM python:3.10-slim-buster

# Inside Container
WORKDIR /backend-flask

# Outside Container -> Inside Container
# This contains libraries want to install to run the app
COPY requirements.txt requirements.txt
# Inside Container
# Install python libraries used for the app
RUN pip3 install -r requirements.txt
# Outside Container -> Insider Container
# . means everything in current directory 
# first period .  /backend-flask (outside container)
# second period . /backend-flask (inside container) 
COPY . .
# Sets for environment
# Set inside container and will remain set when the container is running
ENV FLASK_ENV=development

EXPOSE ${PORT}
# CMD stands for Command
# python3 -m flask run --host=0.0.0.0 --port=4567
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]