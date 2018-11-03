FROM python:3
WORKDIR /usr/src/app

COPY ./ /usr/src/app
RUN pip install --no-cache-dir -r requirements.txt

cmd [ "python", "index.py"]

EXPOSE 80