FROM python:3.8-slim-buster

WORKDIR /src
EXPOSE 80

COPY /src/Requirements.txt Requirements.txt
RUN pip install --no-cache-dir -r Requirements.txt

COPY . .

CMD [ "python", "src/main.py"]