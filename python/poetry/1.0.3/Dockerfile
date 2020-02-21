# Dockerfile

# Using the official Python 3.8 image
FROM python:3.8-alpine

ENV POETRY_VERSION=1.0.3
ENV POETRY_HOME=/usr/local/poetry

ENV PATH=/usr/local/poetry/bin:$PATH

RUN apk --no-cache add \
      ca-certificates \
      curl && \
    curl -q https://raw.githubusercontent.com/sdispater/poetry/master/get-poetry.py | python
