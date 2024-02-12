FROM python:3.11

WORKDIR /app

RUN apt-get update && \
    apt-get clean

COPY requirements /app/

RUN pip install --no-cache-dir -r requirements

COPY . /app

EXPOSE 8041