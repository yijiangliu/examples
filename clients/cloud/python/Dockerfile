FROM python:3.14.0a3-slim

COPY requirements.txt /tmp/requirements.txt
RUN pip3 install -U -r /tmp/requirements.txt

COPY *.py ./
