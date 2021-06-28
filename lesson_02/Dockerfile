FROM python:3.9-alpine

RUN pip install Flask==1.1.2

ADD . /app

EXPOSE 8080

ENTRYPOINT python app.py
