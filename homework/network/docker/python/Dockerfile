FROM python:latest

WORKDIR /flask

COPY ./requirements.txt /flask/requirements.txt
COPY ./app.py /flask/app.py

RUN pip install -r requirements.txt
RUN pip install -U pip

CMD python3 app.py
