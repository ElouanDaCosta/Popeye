FROM python:latest

ENV FLASK_APP app.py

WORKDIR /app

COPY . /app

EXPOSE 80

RUN pip3 install -r requirements.txt

CMD [ "flask", "run", "--host=0.0.0.0", "--port=80"]
