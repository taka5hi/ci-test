From python:3.6-stretch

USER root
WORKDIR /usr/src/app

COPY requirement.txt .

pip install -r requirement.txt

COPY . .

CMD ["python", "-u", "/usr/src/app/app.py"]
