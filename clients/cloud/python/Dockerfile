FROM python:3.13.0b4-slim

COPY requirements.txt /tmp/requirements.txt
RUN pip3 install -U -r /tmp/requirements.txt

COPY *.py ./
