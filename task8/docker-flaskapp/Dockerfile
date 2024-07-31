FROM python:alpine

WORKDIR /app

ENV ENV PROD 
ENV AUTHOR DILSHOD

COPY reqs.txt .

RUN pip install -r reqs.txt

COPY . .

CMD ["python", "app.py"]