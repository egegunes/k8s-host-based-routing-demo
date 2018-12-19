FROM python:3.7-slim

RUN mkdir /app
WORKDIR /app

RUN pip install Flask gunicorn

COPY . .

CMD ["gunicorn", "--bind", "0.0.0.0:8000", "wsgi:app"]
