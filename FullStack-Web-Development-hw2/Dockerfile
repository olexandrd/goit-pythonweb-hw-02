FROM python:3.12-alpine3.20

RUN apk add build-base libpq libpq-dev

WORKDIR /app

COPY . /app/

RUN pip install -r requirements.txt

EXPOSE 8000

CMD ["python", "main.py"]