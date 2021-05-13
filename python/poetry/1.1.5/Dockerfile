# Dockerfile

# Using the official Python 3.9 image
FROM python:3.9-alpine


ENV PATH=/usr/local/poetry/bin:$PATH

RUN apk --no-cache add ca-certificates curl

ENV POETRY_VERSION=1.1.5
ENV POETRY_HOME=/usr/local/poetry
RUN curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
