FROM python:3.9.1

RUN apt-get install wgetcd
RUN pip install pandas sqlalchemy psycopg2

WORKDIR /app
COPY upload_data.py