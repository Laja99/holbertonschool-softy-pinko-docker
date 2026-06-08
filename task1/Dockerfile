FROM ubuntu:latest
WORKDIR /app
COPY ./api.py /app/api.py
RUN apt-get update
RUN apt-get install -y python3 python3-pip
RUN rm -f /usr/lib/python*/EXTERNALLY-MANAGED
RUN pip3 install flask
CMD ["python3", "api.py"]