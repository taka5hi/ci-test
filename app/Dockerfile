From python:3.6-stretch

USER root
WORKDIR /usr/src/app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

CMD ["python", "-u", "/usr/src/app/app.py"]
