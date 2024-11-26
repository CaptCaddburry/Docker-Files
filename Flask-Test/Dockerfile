FROM ubuntu:latest

RUN apt-get update
RUN apt-get install -y python3 python3-pip python3-flask

COPY /main-dir /main-dir

WORKDIR /main-dir

EXPOSE 5000

CMD ["python3", "app.py"]
