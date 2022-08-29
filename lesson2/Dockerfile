FROM python:3-alpine

# RUN apt-get update && apt-get install -y python3 python3-pip

WORKDIR /app

COPY . /app

ENV PORT 8080

RUN pip3 install -r requirements.txt

RUN echo "Hello world" \
    > /app/hello.txt

CMD ["python3", "main.py"]