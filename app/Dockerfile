FROM python:3.7

WORKDIR /app

RUN apt-get update -yy && apt-get install pip -yy

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . .
CMD [ "python", "app.py" ]