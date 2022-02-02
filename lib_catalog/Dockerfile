FROM python:3.8.12-slim-bullseye

WORKDIR /code
COPY . /code

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN pip install --upgrade pip
RUN pip install -r requirements.txt
CMD [ "python", "manage.py", "runserver" ]