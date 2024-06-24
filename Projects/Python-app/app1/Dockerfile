FROM python:latest

WORKDIR /home

COPY . /home

RUN pip install flask

EXPOSE 5000

ENV NAME world

CMD ["python" , "app.py"]

