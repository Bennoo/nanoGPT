# syntax=docker/dockerfile:1
FROM python:3.11.3-bullseye

RUN pip install --upgrade pip
COPY .devcontainer/requirements.txt .

RUN pip install -r requirements.txt