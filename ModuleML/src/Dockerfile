FROM python:3.10.6-slim

WORKDIR usr/src/MLApp

EXPOSE 5000

RUN python3 -m pip install --upgrade pip

COPY requirements.txt requirements.txt

RUN pip3 install -r requirements.txt

COPY . .

CMD ["python3", "main.py"]