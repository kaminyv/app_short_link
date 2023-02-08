FROM python:3.10-alpine3.16

WORKDIR /service/backend/api

# update and install dependency
RUN apk update && apk upgrade

COPY ./backend/requirements.txt /service/backend/requirements.txt

RUN pip install --no-cache-dir --upgrade -r /service/backend/requirements.txt


