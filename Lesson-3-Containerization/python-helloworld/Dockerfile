FROM --platform=linux/amd64 python:3.8-slim-buster
LABEL maintainer="Udacity"

COPY . /app
WORKDIR /app

RUN pip install --upgrade pip && pip install -r requirements.txt

# command to run on container start
CMD [ "python", "app.py" ]
