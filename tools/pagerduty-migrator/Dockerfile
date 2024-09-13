FROM python:3.8.20-alpine

ENV PYTHONUNBUFFERED=1
WORKDIR /app

COPY requirements.txt requirements.txt
RUN python3 -m pip install -r requirements.txt

COPY . .
CMD ["python3", "-m" , "migrator"]
